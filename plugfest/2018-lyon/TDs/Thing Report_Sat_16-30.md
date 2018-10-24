## Thing Report

This report details the results of the test bench as of 18:00, 20.10.2018

* Keti sensors are not reachable. Michael Lagally has been notified about this

* Ocf devices timeout.

* Oracle simulated devices seem to work for most of the interactions
The interactions that do not work send a response saying that cloud service has a problem. Michael Lagally confirmed that this is due to actions not being properly handled.

* Webspeak works. It is capable of pronouncing jibberish data sent by the test bench

* test thing works. It even pointed out an error in the test bench since it rejects if the input data doesn't match what is described.
It has zero errors even though it has 13 interactions

* Panasonic has a port number missing in the TDs. The connection doesn't work with the usual networks, only with phone hotspot. This should be fixed somehow.

* Fujitsu Rotary Light: Pointed out that test bench cannot handle text type. This Thing cannot be properly tested by the test bench since it relies on the JSON schema of the TD to generate requests.