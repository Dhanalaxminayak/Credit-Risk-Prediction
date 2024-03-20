<h1 class="display-3">Credit Risk Case Study in Python</h1>
  <p>Using Support Vector Machine (SVM)</p>
  
  <hr>
<h3> What is Credit risk? </h3>
Credit risk refers to the risk that a borrower may not repay a loan and that the lender may lose the principal of the loan or the interest associated with it. In Banking sector this is an important factor to be considered before approving the loan of an applicant.

<h3> How Is Credit Risk Assessed? </h3>
Credit risks are calculated based on the borrowers' overall ability to repay. To assess credit risk on a consumer loan, lenders look at the five C's: an applicant's credit history, his capacity to repay, his capital, the loan's conditions and associated collateral.

<h3> Problem </h3>
To automate the loan eligibility process based on the customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, we given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.

<h3> Data Variables and Description </h3>
<table>
 <tr> <th align="left">Variable</th> <th align="left">Description</th> </tr>
 <tr> <td>Loan_ID</td> <td>Unique Loan ID</td> </tr>
 <tr> <td>Gender</td> <td>Male/ Female</td> </tr>
 <tr> <td>Married</td> <td>Applicant married (Y/N)</td> </tr>
 <tr> <td>Dependents</td> <td>Number of dependents</td> </tr>
 <tr> <td>Education</td> <td>Applicant Education (Graduate/ Under Graduate)</td> </tr>
 <tr> <td>Self_Employed</td> <td>Self employed (Y/N)</td> </tr>
 <tr> <td>ApplicantIncome</td> <td>Applicant income</td> </tr>
 <tr> <td>CoapplicantIncome</td> <td>Coapplicant income</td> </tr>
 <tr> <td>LoanAmount</td> <td>Loan amount in thousands</td> </tr>
 <tr> <td>Loan_Amount_Term</td> <td>Term of loan in months</td> </tr>
 <tr> <td>Credit_History</td> <td>credit history meets guidelines</td> </tr>
 <tr> <td>Property_Area</td> <td>Urban/ Semi Urban/ Rural</td> </tr>  
 <tr> <td>Loan_Status</td> <td>Loan approved (Y/N)</td> </tr>     
</table>

<h3> Dataset File Given </h3>
* [Credit_Risk_Data](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)
  

 <h2>Index</h2>
 - [Importing Datasets](#ImportingDatasets) 
 - [Finding NULL Values](#FindNULLVal) 
 - [Counting Levels in Datasets](#CountDSLevels) 
 - [Treating NULL Values & Converting Variables into 0's and 1's](#TreatNULLVal) 
 - [Plot and Graphs](#Plots)
 - [Support Vector Machine](#SVM) 
 - [SVM Scatter Plot with Hyperplane](#Hyperplane_Plot)

<a id="head"></a>

