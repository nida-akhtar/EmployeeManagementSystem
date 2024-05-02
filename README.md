The Employee Management System (EMS) is a software application designed to streamline and optimize employee data management within an organization. The system will employ various Data Structures and Algorithms 
(DSA) to ensure efficient data storage, retrieval, and manipulation.
1. Employee Database Management (Hashes Implementation).
2. User Authentication and Authorization.
3. Employee Information Tracking.
4. Performance Evaluation.
5. Computation of Employee allowances and Net Pay based on basic Pay.

Class Diagram


EMS
---------------------------------------------------------------------------------------
+ADMIN_PASSWORD: string;
+HASH_SIZE=10: int;
+hash_table[10]={nullptr}: employee_data*;
+h_rent: float;
+m_allowance: float;
+c_allowance: float;
+n_pay: float;
---------------------------------------------------------------------------------------
+authenticateAdmin(): void;
 +authenticateEmployee(): void;
 +add_data(): void;
 +check_data(): void;
 +pay(): void;
 +display(): void;
 +update_data(): void;
 +delete_data(): void;
 +review(): void;
 +pay2(int id): void;
 +update_data2(int id): void;
 + view_rating(int id): void;
 +hashFunction(int id): int;
