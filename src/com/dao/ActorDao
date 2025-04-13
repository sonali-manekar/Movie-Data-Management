package com.dao;

import java.util.ArrayList;
import java.util.Arrays;
import java.util.HashMap;
import java.util.HashSet;
import java.util.List;
import java.util.Map;
import java.util.Set;

import com.entity.Actor;

public class ActorDao {
//	Scanner obj=new Scanner(System.in);
	Actor actor=null;
	public Map<Integer,Map<String,List<Actor>>> getAllData()
	{
		Map<Integer,Map<String,List<Actor>>> Db=new HashMap<Integer,Map<String,List<Actor>>>();
		Map<String,List<Actor>> db1=new HashMap<String,List<Actor>>();
		List<Actor> l1=new ArrayList<Actor>();
		
		List<String> moviedb0=Arrays.asList("A","B","C");
		List<String> moviedb1=Arrays.asList("D","E","F");
		List<String> moviedb2=Arrays.asList("G","H","I");
		List<String> moviedb3=Arrays.asList("J","K","L");
		List<String> moviedb4=Arrays.asList("M","N","O");
		
		l1.add(new Actor(1995, "John Smith", "$10 million", moviedb0)); 
        l1.add(new Actor(2001, "Jane Doe", "$15 million", moviedb1));
        l1.add(new Actor(2010, "Michael Johnson", "$25 million", moviedb2));
        l1.add(new Actor(2005, "Emily Clark", "$18 million", moviedb3));
        l1.add(new Actor(2018, "David Lee", "$8 million", moviedb4));
         
        db1.put("Jay ho", l1);
        
        List<Actor> l2 = new ArrayList<>();
        List<String> moviedb5 = Arrays.asList("P", "Q", "R");
        List<String> moviedb6 = Arrays.asList("S", "T", "U");
        List<String> moviedb7 = Arrays.asList("V", "W", "X");
        List<String> moviedb8 = Arrays.asList("Y", "Z", "AA");
        List<String> moviedb9 = Arrays.asList("BB", "CC", "DD");

        l2.add(new Actor(1992, "Sarah Connor", "$20 million", moviedb5));
        l2.add(new Actor(1998, "Peter Parker", "$30 million", moviedb6));
        l2.add(new Actor(2004, "Bruce Wayne", "$50 million", moviedb7));
        l2.add(new Actor(2012, "Clark Kent", "$40 million", moviedb8));
        l2.add(new Actor(2016, "Diana Prince", "$35 million", moviedb9));

        db1.put("Victory", l2);

        // List 3 of Actors for key "Blockbuster"
        List<Actor> l3 = new ArrayList<>();
        List<String> moviedb10 = Arrays.asList("EE", "FF", "GG");
        List<String> moviedb11 = Arrays.asList("HH", "II", "JJ");
        List<String> moviedb12 = Arrays.asList("KK", "LL", "MM");
        List<String> moviedb13 = Arrays.asList("NN", "OO", "PP");
        List<String> moviedb14 = Arrays.asList("QQ", "RR", "SS");

        l3.add(new Actor(1990, "Tony Stark", "$100 million", moviedb10));
        l3.add(new Actor(1994, "Steve Rogers", "$75 million", moviedb11));
        l3.add(new Actor(1999, "Natasha Romanoff", "$60 million", moviedb12));
        l3.add(new Actor(2008, "Bruce Banner", "$55 million", moviedb13));
        l3.add(new Actor(2015, "Thor Odinson", "$80 million", moviedb14));

        db1.put("Blockbuster", l3);
        
        Map<String, List<Actor>> db2 = new HashMap<>();

        // New actors for db2 under different keys
        List<Actor> l4 = new ArrayList<>();
        List<String> moviedb15 = Arrays.asList("AAA", "BBB", "CCC");
        List<String> moviedb16 = Arrays.asList("DDD", "EEE", "FFF");
        List<String> moviedb17 = Arrays.asList("GGG", "HHH", "III");
        List<String> moviedb18 = Arrays.asList("JJJ", "KKK", "LLL");
        List<String> moviedb19 = Arrays.asList("MMM", "NNN", "OOO");

        l4.add(new Actor(1985, "Harrison Ford", "$120 million", moviedb15));
        l4.add(new Actor(1990, "Robert De Niro", "$150 million", moviedb16));
        l4.add(new Actor(2003, "Leonardo DiCaprio", "$180 million", moviedb17));
        l4.add(new Actor(2011, "Tom Hardy", "$90 million", moviedb18));
        l4.add(new Actor(2020, "Timothée Chalamet", "$50 million", moviedb19));

        db2.put("Stars of Cinema", l4);

        // Another set of actors
        List<Actor> l5 = new ArrayList<>();
        List<String> moviedb20 = Arrays.asList("PPP", "QQQ", "RRR");
        List<String> moviedb21 = Arrays.asList("SSS", "TTT", "UUU");
        List<String> moviedb22 = Arrays.asList("VVV", "WWW", "XXX");
        List<String> moviedb23 = Arrays.asList("YYY", "ZZZ", "AAA");
        List<String> moviedb24 = Arrays.asList("BBB", "CCC", "DDD");

        l5.add(new Actor(1993, "Brad Pitt", "$200 million", moviedb20));
        l5.add(new Actor(2001, "Matt Damon", "$170 million", moviedb21));
        l5.add(new Actor(2006, "Christian Bale", "$130 million", moviedb22));
        l5.add(new Actor(2014, "Ryan Gosling", "$100 million", moviedb23));
        l5.add(new Actor(2019, "Chris Hemsworth", "$90 million", moviedb24));

        db2.put("Hollywood Legends", l5);
        
        Db.put(2016, db1);
        Db.put(2017, db2);
        return Db;
	}

}
