# Project 1: Cosmological models (25p.)

Project 1 published shortly

In this directory you can find the relevant material for project 1.

Your report should be handed in via Canvas. Carry out the project
in groups of two, and hand in a joint report. Do not forget to hand in
your Python code!

More information can be found in the project write-up in this directory.

The database of supernovas contain information that can be read as, e.g., a panda dataframe. The names specify the content of each column.

```
# read the supernova (cosmological) redshift data
datafile = open('SCPUnion2.1_mu_vs_z.txt','r')
SCP_data = pd.read_table(datafile,comment='#',
                        names=['SN name','Redshift','Distance modulus',
                                   'Distance modulus error','P low mass'])
print(SCP_data)
```

