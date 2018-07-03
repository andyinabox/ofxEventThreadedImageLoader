# ofxEventThreadedImageLoader

Usage its like ofxEventThreadedImageLoader, but if you add:


```
ofAddListener(ofxTILEvent().events,this,&**YourClassName::YourCallback**);
```

You get an event knowing if the image its loaded ok or not, and why.

```
void YourClassName::YourCallback(ofxTILEvent &e) { 
    
	//	e.loaded (true,false) 
    
	//	e.error_msg (string) 

}
```
