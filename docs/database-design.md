# Database Design

## Users

| Field | Type |
|---------|---------|
| user_id | INT |
| username | VARCHAR |
| password | VARCHAR |
| role | VARCHAR |

## Students

| Field | Type |
|---------|---------|
| student_id | INT |
| name | VARCHAR |
| email | VARCHAR |
| course_id | INT |

## Courses

| Field | Type |
|---------|---------|
| course_id | INT |
| course_name | VARCHAR |

## Attendance

| Field | Type |
|---------|---------|
| attendance_id | INT |
| student_id | INT |
| date | DATE |
| status | VARCHAR |

## Reports

| Field | Type |
|---------|---------|
| report_id | INT |
| student_id | INT |
| generated_date | DATE |