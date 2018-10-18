# utl-workstation-vs-eg-server-performance-thought-experiment
Workstation vs EG Server performance thought experiment.
    Workstation vs EG Server performance thought experiment

    github
    https://tinyurl.com/ybx63gwn
    https://github.com/rogerjdeangelis/utl-workstation-vs-eg-server-performance-thought-experiment

      Unscientific thought experiment

      ACADEMIC BENCHMARKS (EG Server vs Power workstation
       (not Big data, big Computation comparison or large grid computing)

       COMPUTE BOUND

          10 minutes -> Workstation 16 cores 100% utlilization    10 minutes
          14 minues  -> EG Server has 256 cores but only 5% utilization available and 10% downtime)

           Workstation 16 cores 100% utlilization    10 minutes
           Server 256 cores (5% availble utilization 10% downtime)

       HIGH MEMORY USAGE (8 tasks each take 6gb each)

           10 minutes Workstation
           10 hours EG server (4gb max ram issue and extreme paging?)

       HIGH I/O (this is where the server can equal the workstation ( all ables <1TB)

           1 hour -> Workstation - You need multithreaded SPDE and at least 2 channel RAID0 SSDs
           1 hour => Server (SAMBA)


     SERVER TASKS

      Big data if single table > 1tb
      Big computation when 64+ cores at 25% system utilization for over a week


     DETAILS

    Throughput is the best measure, the elapsed time of your task.

    Suppose you have a 16 core 32 thread workstation with 64gb ram,  SPDE partitioning and dual ssd raid0 arrays.
    These are not that expensive if you are willing to buy an off lease small server (circa 2008 DDR2)
    server and turn it into a SAS workstation.

    COMPARISON (not big data or big computation)

      Unix Sever has 256 cores, 1025gb ram five boxes, samba i/o, grid server

      However suppose SAS is confined to VMs and users are restricted to
      2 cores, 4gb and whatever syxtem utilization is available

      Also suppose the unix system runs at a constant 95% utilization and
      10% downtime.

      So how do you compare a non big data or big computation task

      First compare a compute bound job that runs at 100% utilization on 16 cores and
      requires less than 4gb total.

      Also suppose the elapsed time in 10 minutes for the job on the workstation

      Server has 256 cores but at 95% utilization only 12.8 cores are avalible.
      Further more at 10% downtime 12.8 - .1*12.8 = 11.5 cores are available.

      The server will take 16/11.5 * 10 minutes or about 14 minutes


