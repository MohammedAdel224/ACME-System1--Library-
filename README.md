<h1 align="center">ACME System 1 Library v24.9.32.2</h1>
<p>This is a library to automate ACME System 1 tasks</p><br/>

* UiPath.System.Activities >= 24.10.4
* UiPath.UIAutomation.Activities >= 24.10.0

<br/>
<br/>
<div>
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_ActivitiesPanel.png" alt="ACME System 1 Activities"/><br/>
</div>
<br/>
<br/>

<details>
<summary><h5>ACME System1 - Close</h5></summary>
<div  align="center">
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_Close_Activity.png" alt="ACME System1 - Close - Activity"/>
</div>

### Annotation
#### Description:
	close ACME System 1 page

#### Post-Condition:
	ACME System 1 closed

 
### Properties
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_Close_Properties.png" alt="ACME System1 - Close - Properties" align="right"/>

#### Retry
* Number Of Retries: The number of times that the activity is to be retried. `(Int32)`
* Retry Interval: Specifies the amount of time (in seconds) between each retry. `(System.TimeSpan)`

#### Post-Condition
* Timeout (milliseconds): `(Int32)`</br>
</br>
</br>
</br>
</br>

<hr/>
</details>



<details>
<summary><h5>ACME System1 - Close Update Work Item Page</h5></summary>
<div  align="center">
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_CloseUpdateWorkItemPage_Activity.png" alt="ACME System1 - Close Update Work Item Page - Activity"/>
</div>

### Annotation
#### Description:
	close ACME System 1 update item page

#### Post-Condition:
	ACME System 1 update item page closed

 
### Properties
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_CloseUpdateWorkItemPage_Properties.png" alt="ACME System1 - Close Update Work Item Page - Properties" align="right"/>

#### Retry
* Number Of Retries: The number of times that the activity is to be retried. `(Int32)`
* Retry Interval: Specifies the amount of time (in seconds) between each retry. `(System.TimeSpan)`

#### Post-Condition
* Timeout (milliseconds): `(Int32)`</br>
</br>
</br>
</br>
</br>

<hr/>
</details>



<details>
<summary><h5>ACME System1 - Extract WI1 Account Information Details</h5></summary>
<div  align="center">
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_ExtractWI1AccountInformationDetails_Activity.png" alt="ACME System1 - Extract WI1 Account Information Details - Activity"/>
</div>

### Annotation
#### Description:
	extract ACME System1 WI1 account information details

#### Pre-Condition:
	ACME System1 WI1 details page is opend

#### Post-Condition:
	ACME System1 WI1 account information details extracted

 
### Properties
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_ExtractWI1AccountInformationDetails_Properties.png" alt="ACME System1 - Extract WI1 Account Information Details - Properties" align="right"/>

#### Retry
* Number Of Retries: The number of times that the activity is to be retried. `(Int32)`
* Retry Interval: Specifies the amount of time (in seconds) between each retry. `(System.TimeSpan)`

#### Pre-Condition
* Timeout (milliseconds): `(Int32)`

#### Post-Condition
* Timeout (milliseconds): `(Int32)`

#### Output
* Client ID `(String)`
* Account Number `(String)`
* Account Amount `(String)`
* Currency `(String)`

<hr/>
</details>



<details>
<summary><h5>ACME System1 - Extract Work Items</h5></summary>
<div  align="center">
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_ExtractWorkItems_Activity.png" alt="ACME System1 - Extract Work Items - Activity"/>
</div>

### Annotation
#### Description:
	return a DataTable contains work items data table on ACME System 1

#### Pre-Condition:
	work items page is opend

#### Post-Condition:
	work items table extracted successfuly

 
### Properties
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_ExtractWorkItems_Properties.png" alt="ACME System1 - Extract Work Items - Properties" align="right">

#### Retry
* Number Of Retries: The number of times that the activity is to be retried. `(Int32)`
* Retry Interval: Specifies the amount of time (in seconds) between each retry. `(System.TimeSpan)`

#### Pre-Condition
* Timeout (milliseconds): `(Int32)`

#### Extraction
* Timeout (milliseconds): `(Int32)`

#### Output
* Work Items: `(System.Data.DataTable)`<br/>
<br/>
<br/>

<hr/>
</details>



<details>
<summary><h5>ACME System1 - Launch</h5></summary>
<div  align="center">
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_Launch_Activity.png" alt="ACME System1 - Launch - Activity"/>
</div>

### Annotation
#### Description:
	open Chrome on the login page of ACME System 1
 
#### Post-Condition:
	ACME System 1 login page is opend


### Properties
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_Launch_Properties.png" alt="ACME System1 - Launch - Properties" align="right">

#### Retry
* Number Of Retries: The number of times that the activity is to be retried. `(Int32)`
* Retry Interval: Specifies the amount of time (in seconds) between each retry. `(System.TimeSpan)`

#### Post-Condition
* Timeout (milliseconds): `(Int32)`<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<hr/>
</details>



<details>
<summary><h5>ACME System1 - Login</h5></summary>
<div  align="center">
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_Login_Activity.png" alt="ACME System1 - Login - Activity"/>
</div>
	
### Annotation
#### Desctiption:
	login to ACME System 1 account
 
#### Pre-Condition:
	ACME System 1 login page is opend

#### Post-Condition:
	ACME System 1 dashboard page is opend

 
### Properties
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_Login_Properties.png" alt="ACME System1 - Login - Properties" align="right">

#### Retry
* Number Of Retries: The number of times that the activity is to be retried. `(Int32)`
* Retry Interval: Specifies the amount of time (in seconds) between each retry. `(System.TimeSpan)`

#### Pre-Condition
* Timeout (milliseconds): `(Int32)`

#### Input
* Email: `(String)`
* Password: `(System.Security.SecureString)`

#### Post-Condition
* Timeout (milliseconds): `(Int32)`
* Check Credentials Timeout (milliseconds): `(Int32)`

#### Output
* Is Credential Correct: `(Boolean)`<br/>
<br/>
<br/>

<hr/>
</details>



<details>
<summary><h5>ACME System1 - Logout</h5></summary>
<div  align="center">
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_Logout_Activity.png" alt="ACME System1 - Logout - Activity"/>
</div>

### Annotation
#### Description:
	logout from ACME System 1 account

#### Pre-Condition:
	ACME System 1 is launched

#### Post-Condition:
	ACME System 1 login page is opend


### Properties
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_Logout_Properties.png" alt="ACME System1 - Logout - Properties" align="right">

#### Retry
* Number Of Retries: The number of times that the activity is to be retried. `(Int32)`
* Retry Interval: Specifies the amount of time (in seconds) between each retry. `(System.TimeSpan)`

#### Pre-Condition
* Timeout (milliseconds): `(Int32)`

#### Post-Condition
* Timeout (milliseconds): `(Int32)`<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<hr/>
</details>



<details>
<summary><h5>ACME System1 - Navigate To Work Item Details</h5></summary>
<div  align="center">
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_NacigateToWorkItemDetails_Activity.png" alt="ACME System1 - Navigate To Work Item Details - Activity"/>
</div>

### Annotation
#### Description:
	navigate to work item detail page using URL or WIID on ACME System 1
#### Pre-Condition:
	account is logged in
#### Post-Condition:
	work item details page opend


### Properties
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_NacigateToWorkItemDetails_Properties.png" alt="ACME System1 - Navigate To Work Item Details - Properties" align="right">

#### Retry
* Number Of Retries: The number of times that the activity is to be retried. `(Int32)`
* Retry Interval: Specifies the amount of time (in seconds) between each retry. `(System.TimeSpan)`

#### Pre-Condition
* Timeout (milliseconds): `(Int32)`

#### URL
* URL: `(String)`
* WIID: `(String)`

#### Post-Condition
* Timeout (milliseconds): `(Int32)`<br/>
<br/>

<hr/>
</details>



<details>
<summary><h5>ACME System1 - Navigate To Work Items</h5></summary>
<div  align="center">
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_NacigateToWorkItems_Activity.png" alt="ACME System1 - Navigate To Work Items - Activity"/>
</div>

### Annotation
#### Description:
	navigate to work items page on ACME System 1
#### Pre-Condition:
	account is logged in
#### Post-Condition:
	work items page opend


### Properties
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_NacigateToWorkItems_Properties.png" alt="ACME System1 - Navigate To Work Items - Properties" align="right">

#### Retry
* Number Of Retries: The number of times that the activity is to be retried. `(Int32)`
* Retry Interval: Specifies the amount of time (in seconds) between each retry. `(System.TimeSpan)`

#### Pre-Condition
* Timeout (milliseconds): `(Int32)`

#### Post-Condition
* Timeout (milliseconds): `(Int32)`<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<hr/>
</details>



<details>
<summary><h5>ACME System1 - Open Update Work Item Page</h5></summary>
<div  align="center">
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_OpenUpdateWorkItemPage_Activity.png" alt="ACME System1 - Open Update Work Item Page - Activity"/>
</div>

### Annotation
#### Description:
	open update work item page on ACME System1
#### Pre-Condition:
	work item details page is opened
#### Post-Condition:
	update work item page opend


### Properties
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_OpenUpdateWorkItemPage_Properties.png" alt="ACME System1 - Open Update Work Item Page - Properties" align="right">

#### Retry
* Number Of Retries: The number of times that the activity is to be retried. `(Int32)`
* Retry Interval: Specifies the amount of time (in seconds) between each retry. `(System.TimeSpan)`

#### Pre-Condition
* Timeout (milliseconds): `(Int32)`

#### Post-Condition
* Timeout (milliseconds): `(Int32)`<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<hr/>
</details>



<details>
<summary><h5>ACME System1 - Update Work Item</h5></summary>
<div  align="center">
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_UpdateWorkItem_Activity.png" alt="ACME System1 - Update Work Item - Activity"/>
</div>

### Annotation
#### Description:
	update work item on ACME System1
#### Pre-Condition:
	update work item page is opened
#### Post-Condition:
	update alert appeard


### Properties
<img src="https://github.com/MohammedAdel224/ACME-System1--Library-/blob/main/Screenshots/ACMESystem_1_UpdateWorkItem_Properties.png" alt="ACME System1 - Update Work Item - Properties" align="right">

#### Retry
* Number Of Retries: The number of times that the activity is to be retried. `(Int32)`
* Retry Interval: Specifies the amount of time (in seconds) between each retry. `(System.TimeSpan)`

#### Pre-Condition
* Timeout (milliseconds): `(Int32)`

#### Input
* Comment: `(String)`
* Status: Open | Completed | Rejected `(String)`

#### Post-Condition
* Timeout (milliseconds): `(Int32)`<br/>
<br/>
<br/>

<hr/>
</details>
