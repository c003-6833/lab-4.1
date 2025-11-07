Which server headers you observed:
http://scanme.nmap.org
http://httpbin.org/
http://example.com/

Were they helpful?
Yes, for http://httpbin.org/ I could see that the service was temporarily unavailible. I could also see the server version for the first two 

Differences between the target sites in headers, titles, forms, and keywords.
Titles: http://scanme.nmap.org = Go ahead and ScanMe!
        http://httpbin.org/ = httpbin.org
        http://example.com/ = Example Domain

Servers: http://scanme.nmap.org =  Apache/2.4.7 (Ubuntu)
         http://httpbin.org/ = Server: gunicorn/19.9.0
         *Important to know as you can check for vulnerablities in these specific versions of the severs*

Defensive use of this information:  can help ensure that no relevant information is missed

Ethical precautions you must follow when performing similar reconnaissance
Do not scan websites that you do not have permission to scan

