# slurm_jobs_analytics
Run analytics on jobs data from sacct

## sacct cmdline to generate data
```
sacct -P -o JobID%20,State,Submit,Start,Elapsed,MaxVMSize -T -S{period_start} -E{period_end} -A {project} -a
```
