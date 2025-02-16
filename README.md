DROP TABLE IF EXISTS Lab_Grades;


CREATE TABLE Lab_Grades (
  std_id CHAR(4) NOT NULL PRIMARY KEY,
  name VARCHAR(30) NOT NULL,
  major CHAR(3) NOT NULL,
  section CHAR(1) NOT NULL,
  days_present INT NOT NULL,
  project_marks FLOAT NOT NULL,
  cgpa DECIMAL(3,2) NOT NULL, 
  submission_date DATE NOT NULL
);


INSERT INTO Lab_Grades VALUES
('s001', 'Abir', 'CS', '1', 10, 18.5, 3.91, '2018-09-15'),
('s002', 'Nafis', 'CSE', '1', 12, 20, 3.86, '2018-08-15'),
('s003', 'Tasneem', 'CS', '1', 8, 18, 3.57, '2018-09-18'),
('s004', 'Nahid', 'ECE', '2', 7, 16.5, 3.25, '2018-08-20'),
('s005', 'Arafat', 'CS', '2', 11, 20, 4.00, '2018-09-13'),
('s006', 'Tasneem', 'CSE', '1', 12, 17.5, 3.70, '2018-08-15'),
('s007', 'Muhtadi', 'ECE', '1', 10, 19, 3.67, '2018-09-16'),
('s008', 'Farhana', 'CSE', '2', 6, 15, 2.67, '2018-08-16'),
('s009', 'Naima', 'CSE', '2', 12, 20, 3.70, '2018-08-14');
