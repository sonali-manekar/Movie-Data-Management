package com.service;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.HashSet;
import java.util.List;
import java.util.Map;
import java.util.Set;

import com.dao.ActorDao;
import com.entity.Actor;

public class ActorService {
	ActorDao dao = null;

	public Map<Integer, Map<String, List<Actor>>> getAllDataService() {
		dao = new ActorDao();
		Map<Integer, Map<String, List<Actor>>> db = dao.getAllData();
		return db;
	}

	public List<Actor> getAllActorsService() {
		dao = new ActorDao();
		Map<Integer, Map<String, List<Actor>>> db = dao.getAllData();
		List<Actor> db1 =new ArrayList<Actor>();
		Set<Integer> yearset = db.keySet();
		for (int year : yearset) {
			Map<String, List<Actor>> db2 = db.get(year);
			for(Map.Entry<String, List<Actor>> entry : db2.entrySet())
			{
				db1.addAll(entry.getValue());
			}
		}
		return db1;
	}

	public List<String> getAllActorByDubutYearService(int year) {
		dao = new ActorDao();
		List<Actor> db1 = this.getAllActorsService();
		List<String> db = new ArrayList<String>();
		for (Actor actor : db1) {
			if(actor.getDebutyear()==year)
			db.add(actor.getFullname());
			}
		return db;
	}
	public Set<String> getAllMovieByYearService(int year)
	{
		dao = new ActorDao();
		Map<Integer, Map<String, List<Actor>>> db = dao.getAllData();
		Set<String> allmovie=new HashSet<String>();
        Set<Integer> set=db.keySet();
        for(int y:set)
        {
        	if(y==year) {
        		allmovie=db.get(y).keySet();
        	}
        }
        return allmovie;
	}

}
