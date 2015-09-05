---
Title:    Test Scheduling Problem
Proposer: Morten Mossige
Category: Scheduling and related problems
---
The problem was presented as the Industrial modelling challenge at CP2015.

The problem arises in the context of a testing facility. A number of tests have to be performed in minimal time. Each test has a given duration and needs to run on one machine. While the test is running on a machine, no other test can use that machine. Some tests can only be assigned to a subset of the machines, for others you can use any available machine.  For some tests, additional, possibly more than one, global resources are needed. While those resources are used for a test, no other test can use the resource. The objective is to finish the set of all tests as quickly as possible, i.e. all start times should be non-negative, and makespan should be minimized. The makespan is the difference between the start of the earliest test, and the end of the latest finishing test.
