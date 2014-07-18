package org.ten.events
{
	import flash.events.Event;

	public class SlideEvent extends Event
	{
		/**
		 * Our Slide Event types.
		 */
		public static const SLIDE_COMPLETE:String = "sideHasCompleted";
		public static const SLIDE_PREVIEW_SCALE:String = "previewScale";
		
		/**
		 * Our event instance variables.
		 */
		public var scale:Number;
		
		public function SlideEvent(type:String, newScale:Number = 0, bubbles:Boolean=false, cancelable:Boolean=false)
		{
			super(type, bubbles, cancelable);
			this.scale = newScale;
		}
		
	}
}