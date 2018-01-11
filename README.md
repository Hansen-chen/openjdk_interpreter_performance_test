# Performance test
Command line:

java -Xint -jar dacapo-9.12-bach.jar -s default avrora eclipse fop h2 jython luindex lusearch pmd sunflow tomcat tradebeans tradesoap xalan

benchmark causes error:
batik

Run all 13 benchmarks once to approximate the performance.

# Result
If we eliminate the largest(1.55) and smallest results(0.71), cpp interpreter's performance is around 80% ~ 103% to template interpreter's performance according to time(msec)
<img src="https://user-images.githubusercontent.com/33415010/34829413-9cd8b7c2-f71b-11e7-96ed-049f5b26c86d.png" />








 
 
