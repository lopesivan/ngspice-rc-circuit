# ngspice-rc-circuit
RC Circuit So, let's go create an RC circuit

The new lines of note are the .ic and the .tran. .ic sets the initial conditions of all nodes. .tran sets the time step, and total time for the transient analysis. If you have both .dc and .tran in a single file, the last one is what will show up in an interpreter. If you do a batch run of course, both will be put into the result file.

