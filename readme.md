#Simple Tracker GA
####A simple AS3 wrapper class for tracking legacy Flash ads with Google Analytics ####

Use this handy script for times when you need to track interaction metrics, but dont necessarily want the overhead of a third-party rich media tracking system. 

I've provided an example FLA file which should get you started. Just replace the test analytics ID with your own.

##Usage##

	import com.toymakerlabs.utils.SimpleTrackerGA;	
	var simpleTracker:SimpleTrackerGA;	
	//replace with your GAID	simpleTracker = new SimpleTrackerGA(this,"UA-XXXXXX");
	//Get Tracking!	simpleTracker.placementID = "TEST-MPU";
	//Track strings, or SimpleTrackerGA constants	simpleTracker.trackEvent("rollOut");	simpleTracker.trackEvent(simpleTracker.trackEvent(simpleTracker.EXPANSION);
