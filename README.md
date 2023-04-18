# Lab-7_202001273

# Name - Joshi Hemangi Sanjaybhai
# Section A

We can have three outcomes:Invalid date,previous date and an error message.

All the inputs in the following ranges 1 <= month <= 12, 1 <= day <= 31, 1900 <= year <= 2015 will be valid and give previous date for output.Numbers out of this range will give an error message as they are invalid inputs.

We will get invalid date message when we enter 1-1-1900 as it is a valid input but previous date is out of range for this input.

### Equivalence Partitioning Test Cases:
<table>
  <tr>
    <th>Tester Action and Input Data</th>
    <th>Expected Outcome</th>
  </tr>
  <tr>
    <td>Valid input: day=31, month=12, year=2015</td>
    <td>Previous date</td>
  </tr>
  <tr>
    <td>Valid input: day=1, month=1, year=1900</td>
    <td>Invalid date</td>
  </tr>
  <tr>
    <td>Valid input: day=8, month=10, year=2003</td>
    <td>Previous date</td>
  </tr>
  <tr>
    <td>Invalid input: day=0, month=8, year=2014</td>
    <td>An error message</td>
  </tr>
  <tr>
    <td>Valid input: day=22, month=6, year=1996</td>
    <td>Previous date</td>
  </tr>
  <tr>
    <td>Invalid input: day=6, month=41, year=2018</td>
    <td>An error message</td>
  </tr>
  <tr>
    <td>Invalid input: day=35, month=20, year=2001</td>
    <td>An error message</td>
  </tr>
</table>

<b>Previous dates:</b>
<table>
  <tr>
    <th>Date</th>
    <th>Previous Date</th>
  </tr>
  <tr>
    <td>31-12-2015</td>
    <td>30-12-2015</td>
  </tr>
  <tr>
    <td>8-10-2003</td>
    <td>7-10-2003</td>
  </tr>
  <tr>
    <td>22-6-1996</td>
    <td>21-6-1996</td>
  </tr>
</table>


### Boundary Value Analysis Test Cases:

<table>
  <tr>
    <th>Tester Action and Input Data</th>
    <th>Expected Outcome</th>
  </tr>
  <tr>
    <td> Earliest possible date: day=1,month=1,year=1900</td>
    <td>Invalid date</td>
  </tr>
  <tr>
    <td>Latest possible date: day=31,month=12,year=2015</td>
    <td>Previous date(30-12-2015)</td>
  </tr>
  <tr>
    <td>One day before earliest date: day=31,month=12,year=1899</td>
    <td>An error message</td>
  </tr>
  <tr>
    <td>One day after latest date: day=1,month=1,year=2016</td>
    <td>An error message</td>
  </tr>
  <tr>
    <td>Invalid date: day=39, month=4, year=2000</td>
    <td>An error message</td>
  </tr>
  <tr>
    <td>Valid date: day=12, month=6, year=2002</td>
    <td>Previous date(11-6-2002)</td>
  </tr>
  <tr>
    <td>Valid date: day=30, month=8, year=2010</td>
    <td>Previous date(29-8-2010)</td>
  </tr>
</table>
</br>
