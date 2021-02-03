SQL Aggregate Functions (Count , Max , Min , Sum , Avg)


Step 1 - Create the Emp Table using below query

CREATE TABLE EMP (EMP_ID INT , EMP_NAME VARCHAR(100) , DEPARTMENT VARCHAR(100) ,SALARY INT);

Step 2 Insert the following six Records into the table by running the below query

INSERT INTO EMP VALUES 
(1, 'TIN' ,'HR', 1000), 
(2, 'JON' ,'HR', 2000), 
(3, 'MONA' ,'IT', 5000),
(4, 'DAVID' ,'IT',3000),
(5, 'DON' ,'MKT',2000),
(6, 'TIM' ,'MKT',NULL);

Step 3 : verify the records are inserted successfully by executing below query

SELECT * FROM EMP;

Step 4 : Now Practice Aggregate functions by executing below queries
 
SELECT COUNT(*) FROM EMP;
SELECT COUNT(SALARY) FROM EMP;
SELECT  COUNT(DISTINCT SALARY) FROM EMP;


SELECT  MAX(SALARY) FROM EMP;
SELECT  MIN(SALARY) FROM EMP;

SELECT SUM (SALARY) FROM EMP;
SELECT   SUM(DISTINCT SALARY) FROM EMP;

SELECT   AVG(SALARY) FROM EMP;
SELECT   AVG(DISTINCT  SALARY) FROM EMP;

