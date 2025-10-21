Project: weblog-analyzer
Aothors: David J. Barnes and Michael Kölling

This project is part of the material for chapter 7 of the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling


Purpose of project: To provide an illustration of the use of arrays.
How to start this project: Create a LogAnalyzer object.

The LogfileReader expects to read a file, weblog.txt,
containing lines of data in the format:

    year month day hour minute

month values are in the range 1-12 and day values in the range 1-31.
If the sample file cannot be found, the reader will create some simulated
data. Alternatively, use the LogfileCreator to create some random data.
Use its createFile method to give a file name and the number of entries
to create.

PART 1 [weblog-analyzer project]
Q1: 18: 237

Q2: Person[] people;

Q3: boolean[]vacant;
// the rest is for notes.
    for(int hour = 0; hour < hourCounts.lenghth; hours++){
   if(hourCounts[hour]==0){
    vacant[hour]true;
else
    vacant[hour]false;
   }
}

Q4: 5 times

Q5: int[]counts;
    boolean[]occupied = new boolean[5000];

Q6: double[] readings = new double[60];
    String[] urls = new String [90];
    TicketMachine [] machines = new TicketMachine[5];

Q7: 20 objects

Q8: 

Q9: it shows error due to the fact that there is no index 5 space. (0,1,2,3,4)

Q11: 
/** * Print all the values in the marks array that are greater than mean.
 * @param marks An array of mark values.
 * @param mean The mean (average) mark. */
public void printGreater(double marks, double mean) {
for(index = 0; index < marks.length; index++) {
if(marks[index] > mean) {
System.out.println(marks[index]);
}
}


Q12: public LogAnalyzer(String filename)
    {
       hourCounts = new int[HOURS_PER_DAY];
       reader = new LogfileReader(filename);
     }

Q13: 
