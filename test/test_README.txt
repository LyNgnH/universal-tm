test_run_accept includes tests that should accept, and test_run_reject has tests that should reject.
The files can both be used from within main.jff:
Input > Multiple Run (Transducer) > Load Inputs

test_batch.txt includes all tests, along with whether they should accept or reject. 
Tests are grouped by their transition graph, with different inputs applied to them.
test_batch.txt does NOT work from Input > Multiple Run (Transducer). 
It should be used in JFLAP's batch mode.
To access batch testing, go to main menu, then select Batch > Batch Test, and select the appropriate files.

When running a test, there will likely be 1000+ configurations. Just keep pressing OK on the popups. 
But once it gets into the millions of configurations, that probably means there's a problem somewhere.