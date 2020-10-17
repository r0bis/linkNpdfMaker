# shortlink PDF and CSV maker

Script input file is placed in directory data/ and it is named `idListIn.csv`

It must contain the following fields:

- **Name**, **Surname**, **SHASUM**, **TxType**, **StartDate**, **EndDate**

Other input fields are not essential:

- ShortLinks1 (and 2) - get inserted into the table if not present

- Same goes for LongLinks1 and 2 as well as ShortLink names - you will see these fields in the output.

- There are also fields for RIO number, individual and group therapist names and a field for general notes. They are not used for now. 

Column names should occupy the first row of the CSV file.

Please pay attention to spelling of the column names.

Make sure that that **data file** is kept strictly **confidential** - do not put it on GitHub or any other public space. When you work with it, it must stay on safe, encrypted computer, best if it is on your trust computer.

**PDF output** also must be kept strictly confidential.  The **CSV output** is less risky, but still contains actual links used - and even though patient names cannot be learned, it would be a bad idea to expose actual links used to public.  

For that reason repository is set up not to track and upload input and output files.
