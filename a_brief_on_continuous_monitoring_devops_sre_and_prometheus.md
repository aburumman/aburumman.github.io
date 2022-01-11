# A brief on continuous monitoring devops and sre

The more complex an infrastructure the more points of failure and risks, When we have an high level of interdependencies then we need a strategy and infrastructure of high availability to have an highly resilient system and reliability of production systems. Here a continuous monitoring strategy is a critical first step in managing our risk, build an highly reliable and well architected production system. 

Prometheus is an open source tool used for continuous monitoring in devops, it is used to monitor cloud infrastructures, one of the core practices of devops and sre is continuous monitoring, while there are several continuous monitoring tools out there
such as datadog, nagios, splunk etc. prometheus is the quite most popular open source choice.
In the CNCF landscape there's an entire section dedicated to monitoring and observability.

Let's take a brief look at logging and monitoring, logging simply checks what;s going on in our application or infrastructure and monitoring checks how much of activity is taking place ie data about rate of change occurring.

The metrics is the value of state of resource we are trying to measure, the prometheus server collects the data metrics in a time series database and stores them locally
or remotely and displays them in a GUI.

Prometheus was created to monitor highly dynamic container environment like kubernetes, docker swarm etc. it can also be used in traditional non-container environment such as bare servers with apps deployed in them, modern devops became more complex and therefore needs more automation.

Most of the time we have servers runnig multiple applications and hundreds of processes running, with things interconnected. Managing such infrastructure running at various locations having no insight on what is going different layer of our infrastructures architecture such as errors, response latency, hardware failure,resource exhaustion etc. 

A typical scenario I've experienced multiple times is where there is a failure in the system somewhere an you have absolutely no idea the root cause of this failure in an highly interwoven system
It would bring a great deal of frustration isolating the root cause and pressure counts to the mount as you approach your SLO limits.

So having a system such as prometheus identifying and alerting on issues before fatal failures occur is key Creating a continuous monitoring strategy and site reliability system with prometheus is quintessential for a reslilient and well architect-edproduction system.

For opinions, suggestions and contributions 

Contact at: thekubernetesengineer@gmail.com

Read more: https://t.me/thekubernetesengineer