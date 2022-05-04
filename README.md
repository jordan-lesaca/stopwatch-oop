const sw = new Stopwatch()
this object has a few member
duration - property
three methods - reset, start, stop
duration starts at 0
if we call sw.start() twice, we should get an error because the stopwatch should have already started
if we call sw.stop() twice, we should get an error because the stopwatch shoul have already stopped
sw.duration should return us the seconds between when we called start and stop
sw.reset() should take stopwatch from initial state