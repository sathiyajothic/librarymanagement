# library-management-system
Library Management System Project in Python

****Requirements and Installation****

Use pip3 instead of pip for Linux and Mac.

Install PyMySQL
☛pip install PyMySQL

Install Tkinter
☛pip install tk



****Install MySQL server****



****Create a Database and Two Tables****
☛Create a table "book_list" under the "library_management" database

create table book_list(
	book_id VARCHAR(10) NOT NULL,
	book_name VARCHAR(50) NOT NULL,
	author VARCHAR(50) NOT NULL,
	edition VARCHAR(10) NOT NULL,
	price Int(6) NOT NULL,
	qty Int(4) NOT NULL,
	PRIMARY KEY ( book_id )
);

☛Create a table "borrow_record" under the same database
create table borrow_record(
	book_id VARCHAR(10) NOT NULL,
	book_name VARCHAR(50) NOT NULL,
	stu_roll VARCHAR(15) NOT NULL,
	stu_name VARCHAR(50) NOT NULL,
	course VARCHAR(10) NOT NULL,
	subject VARCHAR(30) NOT NULL,
	issue_date date NOT NULL,
	return_date date NOT NULL
);

SAMPLE SCREENSHOTS

![Screenshot 2025-05-15 230017](https://github.com/user-attachments/assets/aaf7eaf1-a5e1-460a-a49f-4af0411e85b5)


![Screenshot 2025-05-15 230131](https://github.com/user-attachments/assets/ce03b67b-3722-4c0d-9142-8a7b77012dbf)


![Screenshot 2025-05-15 230505](https://github.com/user-attachments/assets/9ac44be6-ee66-4aba-b513-c8bf53545665)


![Screenshot 2025-05-15 230539](https://github.com/user-attachments/assets/8d8127ff-1c42-43dd-9300-c354965d12c4)



