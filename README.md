# Spring_flow 
 
Steps to create the files : 
  
Create file in the order > Top to bottom approach:   

# constant/DatabaseConstant.java : declare the table and table alias  
# entity/modulename : table creation to database 
# dao/modulenameDao : data access object 
# dto/modulenameDto : transfer data between layers 
# service/modulenameService : service layer 
# querybuilder : write queries such as getList,getByID 
# manager/modulenameManager : manager layer 
# controller/modulenameController : endpoint delcare and calls to endpoint (CRUD)
