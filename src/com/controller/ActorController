package com.controller;

import java.util.List;
import java.util.Map;
import java.util.Set;

import com.entity.Actor;
import com.service.ActorService;

public class ActorController {
	ActorService service=null;
	public Map<Integer,Map<String,List<Actor>>> getAllDataControl()
	{
		service=new ActorService();
		Map<Integer,Map<String,List<Actor>>> db=service.getAllDataService();
		return db;
	}
	public List<Actor> getAllActorsControl(){
		service=new ActorService();
		List<Actor> db=service.getAllActorsService();
		return db;		
	}
	public List<String> getAllActorByDubutYearControl(int year)
	{
		service=new ActorService();
		List<String> db=service.getAllActorByDubutYearService(year);
		return db;
	}

	public Set<String> getAllMovieByYearControl(int year){
		service=new ActorService();
		Set<String> db=service.getAllMovieByYearService(year);
		return db;
	}
}
