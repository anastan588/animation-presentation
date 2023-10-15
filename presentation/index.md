# Anastasiya Andronava 

## Video:
<https://youtu.be/-oEsVoQZK2g>

## Reveal presentation's deploy:
<https://rolling-scopes-school.github.io/anastan588-JSFE2023Q1/presentation-reveal/>

## Text transcript reference:
<https://docs.google.com/document/d/13cC7UE3iicsl4AEsPYM0X_xBDtCTcFsx/edit?usp=sharing&ouid=111757042662273353571&rtpof=true&sd=true>

Hello) Today I want you to tell about animation in Java Script.
Animation
The Animation interface of the Web Animations API represents a single animation player and provides playback controls and a timeline for an animation node or source. 

Constructor
Animation()
Creates a new Animation object instance.

Instance properties

Animation.currentTime 
Returns and sets the current time value of the animation in milliseconds, whether running or paused. If the animation lacks a timeline, is inactive or hasn't been played yet, its value is  null.

Animation.effect
Gets and sets the target effect of an animation. The target effect may be either an effect object of a type based on AnimationEffect, such as KeyframeEffect, or null.

Animation.finished 
The Animation.finished read-only property of the Web Animations API returns a Promise which resolves once the animation has finished playing.

Animation.id
Gets and sets the String used to identify the animation.

Animation.pending
Indicates whether the animation is currently waiting for an asynchronous operation such as initiating playback or pausing a running animation. True if the animation is pending, false otherwise.

Animation.playbackRate 
Returns or sets the playback rate of the animation. True if the animation is pending, false otherwise. The playback rate is initially 1. Takes a number that can be 0, negative, or positive. Negative values reverse the animation. The value is a scaling factor, so for example a value of 2 would double the playback
rate.

Animation.playState 
Returns an enumerated value describing the playback state of an animation.

Animation.ready
Returns a Promise which resolves when the animation is ready to play.

Animation.replaceState
Indicates whether the animation has been removed by the browser automatically after being replaced by another animation.

Animation: startTime
Is a double-precision floating-point value which indicates the scheduled time when an animation's playback should begin

Animation.timeline
Returns or sets the timeline associated with this animation

Instance methods

cancel()
Clears all KeyframeEffects caused by this animation and aborts its playback.

commitStyles()
Writes the computed values of the animation's current styles into its target element's style attribute. commitStyles() works even if the animation has been automatically removed.
finish()
Sets the current playback time to the end of the animation сorresponding to the current playback direction.
pause()
Suspends playback of the animation.
persist()
Explicitly persists an animation, preventing it from being automatically removed when it is replaced by another animation.
play()
Starts or resumes playing of an animation. If the animation is finished, calling play() restarts the animation, playing it from the beginning.
reverse()
Reverses the playback direction, meaning the animation ends at its beginning. If called on an unplayed animation, the whole animation is played backwards. If called on a paused animation, the animation will continue in reverse
updatePlaybackRate()
Sets the speed of an animation after first synchronizing its
playback position.

Events
cancel
Fired when the Animation.cancel() method is called.
finish
Fired when the animation finishes playing, either when the animation completes naturally, or when the Animation.finish() method is called to immediately cause the animation to finish up.
remove 
Fires when the animation is automatically removed by the browser.

Thank you for your attention :)

