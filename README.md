(1): Using "ping":

What were the min/avg/max/stddev statistics for each?
Amazon:
    min: 4.566 ms
    avg: 12.64 ms
    max: 33.795 ms
    stddev: 11.043878894664

Google:
    min: 4.597
    avg: 6.5316
    max: 6.469
    stddev: 0.78160651865245

Microsoft
    min: 4.832
    avg: 4.932
    max: 7.133
    stddev: 0.86092773215875

Was there any packet loss on any of the pings?

1. one of the package is lost when transmitting to microsoft

Did the IP address change for a given website between pings?

1. NO

(2): Using "tracert":

What was the target server's IP address?
www.amazon.com: 18.172.169.208
www.google.com: 142.250.217.100
www.microsoft.com: 23.216.81.152

How many hops were needed to reach the target?
www.amazon.com: 7
www.google.com: 7
www.microsoft.com: 7

Can you identify your ISP from the intermediate server DNS names?


Identify the "class" of IP address for each major step in the trip
www.amazon.com: A
www.google.com: B
www.microsoft.com: A

(3): Using "ngrok"

can't find the server

(4): Extra credit: Using packet-capture tools:

the picture is in the Question 4 directory

(5): Extra credit: Spy on your opponents (2 pts)

I open an online game that plays chinese card with other online players, then I
opened the wireShark, at the beginning, there are just so many packages in the
wireshark, I found the ip address of the game I am play by using ping
then filtered out the ip address, the picture is in the question 5 folder

(6): Extra credit: Insecure web server:
I found it in the post request, the picture is in the question 6 directory