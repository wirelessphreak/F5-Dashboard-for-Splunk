# F5-Dashboard-for-Splunk

Since the F5 app for spunk has been abandoned I have been playing around with a simple F5 Splunk dashboard. 
This dashboard can be a quick one stop health view for any application being load balanced by the F5. 

Prerequisites are: 
Your F5 LTM and or ASM is logging HSL (high speed logging) to Splunk. 
You have the current iRule associated with virtual servers you want to monitor. 
You have set up an ASM logging profile to send to Splunk. 
Lastly go hear to get the newest iRule for F5 to log to Splunk. https://docs.splunk.com/Documentation/AddOns/released/F5BIGIP/Setup
