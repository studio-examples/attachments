attachments
===========
This example shows how to split XML input data using Splitter component, map Object to CSV and how to add an attachment to an email.

Step 1: run src/main/app/import_orders.sql to create a DB table
Step 2: import the project. you will need a company DB you created in the querying SQL db example.
Step 3: edit common.properties file (mail.to)
Step 4: run mule app
Step 5: make a POST request using postman and following xml:

<root>
    <employees>
        <employee>Chava Puckett</employee>
        <employee>Neil Ford</employee>
        <employee>Daryl Wolfe</employee>
    </employees>
</root>

Step 5: verify that you recieved an email with the attachment = csv file of employee records.