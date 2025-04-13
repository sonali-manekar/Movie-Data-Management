package com.client;

//import java.util.HashMap;
import java.util.List;

import java.util.Map;
import java.util.Scanner;
import java.util.Set;

import com.controller.ActorController;
import com.entity.Actor;

public class TestAllData {
	ActorController ac = new ActorController();
	Scanner sc = new Scanner(System.in);

	public void menu() {
		while (true) {
			System.out.println(
					"Welcome to menu driven project : \n\n1. Get All Data\n2. Get All Actors\n3. Get Actors Name By Thier Debut Date \n4. Get Movies By year  \n5. Exit\n----------------------------------------------------------------");
			System.out.print("\nEnter your choice : ");
			int n = sc.nextInt();
			if(n!=5)
			System.out.println("\nResult : \n");
			switch (n) {
			case 1:
				Map<Integer, Map<String, List<Actor>>> db = ac.getAllDataControl();
				System.out.println(db+"\n");
				break;
			case 2:
				List<Actor> db1 = ac.getAllActorsControl();
				for (Actor actor : db1) {
					System.out.println(actor.getFullname() + " : " + actor.getDebutyear());
				}
				System.out.println();
				break;
			case 3:
				System.out.print("Enter debut year : ");
				int m=sc.nextInt();
				List<String> db2 = ac.getAllActorByDubutYearControl(m);
				for (String name : db2) {
					System.out.println(name);
//					count++;
				}
				System.out.println();
				break;
			case 4:	
				System.out.print("Enter year : ");
				int y=sc.nextInt();
				Set<String> db3=ac.getAllMovieByYearControl(y);
				for(String s:db3)
				{
					System.out.println(s);
				}
				System.out.println();
				break;
			case 5:
				System.out.println("- Thank you for using this service.");
				System.exit(0);
			}
		}

	}

	public static void main(String[] args) {

		TestAllData ta = new TestAllData();
		ta.menu();
//		Map<Integer,Map<String,List<Actor>>> db=ac.getAllDataControl();
//		List<Actor> db1=ac.getAllActorsControl();
//		List<String> db2=ac.getAllActorByDubutYearControl(2005);
//		int count=0;
//		for(Actor actor:db1)
//		{
//			System.out.println(actor.getFullname()+" : "+actor.getDebutyear());
//			count++;
//		}
//		System.out.println("-----------------------------------------------");
//		for(String name:db2)
//		{
//			System.out.println(name);
////			count++;
//		}
//		System.out.println(count);
//		System.out.println(db1);
//		Set<String> set=db1.keySet();
//		int count=0;
//		for(String s:set) {
//			for(Actor actor:db1.get(s)) {
//				System.out.println(actor);
//				count++;
//			}
//		}
//		System.out.println("\n"+count);
//		System.out.println("-------------------------------------");
//		List<String> l1=ac.getAllActorByDubutYearControl(2001);
//		for(String s:l1)
//		{
//			System.out.println(s);
//		}

//		System.out.println(db);

//		Set<Integer> yearset=db.keySet();
//		for(int year:yearset) {
////			System.out.println(db.get(2017));
//			Map<String, List<Actor>> innerMap = db.get(year);
//		    for (Map.Entry<String, List<Actor>> entry : innerMap.entrySet()) {
//		        String key = entry.getKey();               // Key (String)
//		        List<Actor> actorList = entry.getValue();  // Value (List<Actor>)
//		        // Process the key and actorList as needed
//		        System.out.println("Key:-> " + key + "\nActors:-> " + actorList+"\n");
//		    }
//		}

	}

}
