<h1>Employee Burnout Prediction </h1><br>
Employee burnout is a state of physical, emotional and mental exhaustion caused by excessive and prolonged stress. It can have serious consequences on an individual's well-being and can lead to decreased productivity and job performance. In today's fast-paced and constantly connected world, it is increasingly important to recognize and address the signs of burnout in order to maintain the health and well-being of employees.<br>

As part of a final project for  IBM SkillBuild profesional certificate, we will be exploring the use of regression techniques to predict employee burnout. By analyzing a dataset containing various factors that may contribute to burnout such as workload, mental fatigue job and work-life balance, we can develop a model to identify individuals who may be at risk of burnout. By proactively addressing these risk factors, organizations can help prevent burnout and promote the well-being of their employees.<br>

Dataset: Are Your Employees Burning Out?<br>
This dataset consists of 9 columns as follows:<br>

Employee ID: The unique ID allocated for each employee (example: fffe390032003000)<br>
Date of Joining: The date-time when the employee has joined the organization (example: 2008-12-30)<br>
Gender: The gender of the employee (Male/Female)<br>
Company Type: The type of company where the employee is working (Service/Product)<br>
WFH Setup Available: Is the work from home facility available for the employee (Yes/No)<br>
Designation: The designation of the employee of work in the organization. In the range of [0.0, 5.0] bigger is higher designation.<br>
Resource Allocation: The amount of resource allocated to the employee to work, ie. number of working hours. In the range of [1.0, 10.0] (higher means more resource)<br>
Mental Fatigue Score: The level of fatigue mentally the employee is facing. In the range of [0.0, 10.0] where 0.0 means no fatigue and 10.0 means completely fatigue.<br>
Burn Rate: The value we need to predict for each employee telling the rate of Bur out while working. In the range of [0.0, 1.0] where the higher the value is more is the burn out.
