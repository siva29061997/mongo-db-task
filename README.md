1.Users
 db.users.find().pretty()
{
        "_id" : ObjectId("6326865a0cbe2b41a9209b12"),
        "userId" : 1,
        "name" : "ajith",
        "batchNo" : 1,
        "companyDriveId" : 1,
        "coursId" : 1,
        "taskSumissionStatus" : "yes",
        "attendanceId" : 1,
        "attendanceStatus" : "present",
        "companyDriveDate" : "15th Oct",
        "noOfCompanyDriveAttended" : 2,
        "topicId" : 1,
        "taskId" : 1,
        "codekataId" : 1
}
{
        "_id" : ObjectId("6326865a0cbe2b41a9209b13"),
        "userId" : 2,
        "name" : "vijay",
        "batchNo" : 1,
        "companyDriveId" : 2,
        "coursId" : 1,
        "taskSumissionStatus" : "yes",
        "attendanceId" : 2,
        "attendanceStatus" : "present",
        "companyDriveDate" : "16th Oct",
        "noOfCompanyDriveAttended" : 2,
        "topicId" : 2,
        "taskId" : 2,
        "codekataId" : 2
}
{
        "_id" : ObjectId("6326865a0cbe2b41a9209b14"),
        "userId" : 3,
        "name" : "karthik",
        "batchNo" : 1,
        "companyDriveId" : 3,
        "coursId" : 1,
        "taskSumissionStatus" : "yes",
        "attendanceId" : 3,
        "attendanceStatus" : "present",
        "companyDriveDate" : "21st Oct",
        "noOfCompanyDriveAttended" : 2,
        "topicId" : 3,
        "taskId" : 3,
        "codekataId" : 3
}
{
        "_id" : ObjectId("6326865a0cbe2b41a9209b15"),
        "userId" : 4,
        "name" : "surya",
        "batchNo" : 1,
        "companyDriveId" : 4,
        "coursId" : 1,
        "taskSumissionStatus" : "no",
        "attendanceId" : 4,
        "attendanceStatus" : "absent",
        "companyDriveDate" : "22nd Oct",
        "noOfCompanyDriveAttended" : 2,
        "topicId" : 4,
        "taskId" : 4,
        "codekataId" : 4
}
{
        "_id" : ObjectId("6326865a0cbe2b41a9209b16"),
        "userId" : 5,
        "name" : "vicram",
        "batchNo" : 1,
        "companyDriveId" : 5,
        "coursId" : 1,
        "taskSumissionStatus" : "no",
        "attendanceId" : 5,
        "attendanceStatus" : "absent",
        "companyDriveDate" : "23rd Oct",
        "noOfCompanyDriveAttended" : 2,
        "topicId" : 5,
        "taskId" : 5,
        "codekataId" : 5
}
{
        "_id" : ObjectId("6326865a0cbe2b41a9209b17"),
        "userId" : 6,
        "name" : "siva",
        "batchNo" : 1,
        "companyDriveId" : 6,
        "coursId" : 1,
        "taskSumissionStatus" : "no",
        "attendanceId" : 6,
        "attendanceStatus" : "absent",
        "companyDriveDate" : "27th Oct",
        "noOfCompanyDriveAttended" : 2,
        "topicId" : 6,
        "taskId" : 6,
        "codekataId" : 6
}
{
        "_id" : ObjectId("6326865a0cbe2b41a9209b18"),
        "userId" : 7,
        "name" : "mahesh",
        "batchNo" : 1,
        "companyDrived" : 7,
        "coursId" : 1,
        "taskSumissionStatus" : "no",
        "attendanceId" : 7,
        "attendanceStatus" : "absent",
        "companyDriveDate" : "30th Oct",
        "noOfCompanyDriveAttended" : 2,
        "topicId" : 7,
        "taskId" : 7,
        "codekataId" : 7
}
{
        "_id" : ObjectId("6326865a0cbe2b41a9209b19"),
        "userId" : 8,
        "name" : "pasupathi",
        "batchNo" : 1,
        "companyDriveId" : 8,
        "coursId" : 1,
        "taskSumissionStatus" : "no",
        "attendanceId" : 8,
        "attendanceStatus" : "absent",
        "companyDriveDate" : "31st Oct",
        "noOfCompanyDriveAttended" : 2,
        "topicId" : 8,
        "taskId" : 8,
        "codekataId" : 8
}

2.codekata
db.codekata.find().pretty()
{
        "_id" : ObjectId("63268be7637745c54e0fff14"),
        "codekataId" : 1,
        "noOfCodekataProblemsSolved" : 70
}
{
        "_id" : ObjectId("63268be7637745c54e0fff15"),
        "codekataId" : 2,
        "noOfCodekataProblemsSolved" : 60
}
{
        "_id" : ObjectId("63268be7637745c54e0fff16"),
        "codekataId" : 3,
        "noOfCodekataProblemsSolved" : 50
}
{
        "_id" : ObjectId("63268be7637745c54e0fff17"),
        "codekataId" : 4,
        "noOfCodekataProblemsSolved" : 70
}
{
        "_id" : ObjectId("63268be7637745c54e0fff18"),
        "codekataId" : 5,
        "noOfCodekataProblemsSolved" : 50
}
{
        "_id" : ObjectId("63268be7637745c54e0fff19"),
        "codekataId" : 6,
        "noOfCodekataProblemsSolved" : 40
}
{
        "_id" : ObjectId("63268be7637745c54e0fff1a"),
        "codekataId" : 7,
        "noOfCodekataProblemsSolved" : 30
}
{
        "_id" : ObjectId("63268be7637745c54e0fff1b"),
        "codekataId" : 8,
        "noOfCodekataProblemsSolved" : 20
}

3.attendance
 db.attendance.find().pretty()
{
        "_id" : ObjectId("63268d94637745c54e0fff1c"),
        "attendanceId" : 1,
        "attendanceStatus" : "present"
}
{
        "_id" : ObjectId("63268d94637745c54e0fff1d"),
        "attendanceId" : 2,
        "attendanceStatus" : "present"
}
{
        "_id" : ObjectId("63268d94637745c54e0fff1e"),
        "attendanceId" : 3,
        "attendanceStatus" : "present"
}
{
        "_id" : ObjectId("63268d94637745c54e0fff1f"),
        "attendanceId" : 4,
        "attendanceStatus" : "absent"
}
{
        "_id" : ObjectId("63268d94637745c54e0fff20"),
        "attendanceId" : 5,
        "attendanceStatus" : "absent"
}
{
        "_id" : ObjectId("63268d94637745c54e0fff21"),
        "attendanceId" : 6,
        "attendanceStatus" : "absent"
}
{
        "_id" : ObjectId("63268d94637745c54e0fff22"),
        "attendanceId" : 7,
        "attendanceStatus" : "absent"
}
{
        "_id" : ObjectId("63268d94637745c54e0fff23"),
        "attendanceId" : 8,
        "attendanceStatus" : "absent"
}
4.topics
db.topics.find().pretty()
{
        "_id" : ObjectId("63268fd1637745c54e0fff24"),
        "topicId" : 1,
        "topicTaughtMonth" : "october",
        "topic" : "html"
}
{
        "_id" : ObjectId("63268fd1637745c54e0fff25"),
        "topicId" : 2,
        "topicTaughtMonth" : "october",
        "topic" : "css"
}
{
        "_id" : ObjectId("63268fd1637745c54e0fff26"),
        "topicId" : 3,
        "topicTaughtMonth" : "october",
        "topic" : "javascript"
}
{
        "_id" : ObjectId("63268fd1637745c54e0fff27"),
        "topicId" : 4,
        "topicTaughtMonth" : "october",
        "topic" : "node js"
}
{
        "_id" : ObjectId("63268fd1637745c54e0fff28"),
        "topicId" : 5,
        "topicTaughtMonth" : "october",
        "topic" : "mongo db"
}
{
        "_id" : ObjectId("63268fd1637745c54e0fff29"),
        "topicId" : 6,
        "topicTaughtMonth" : "october",
        "topic" : "express"
}
{
        "_id" : ObjectId("63268fd1637745c54e0fff2a"),
        "topicId" : 7,
        "topicTaughtMonth" : "october",
        "topic" : "react"
}
{
        "_id" : ObjectId("63268fd1637745c54e0fff2b"),
        "topicId" : 8,
        "topicTaughtMonth" : "october",
        "topic" : "bootstrap"
}
5.tasks
db.task.find().pretty()
{
        "_id" : ObjectId("632695f9637745c54e0fff3c"),
        "taskId" : 1,
        "taskTaughtMonth" : "october",
        "taskSumissionStatus" : "yes",
        "task" : "meckup api"
}
{
        "_id" : ObjectId("632695f9637745c54e0fff3d"),
        "taskId" : 2,
        "taskTaughtMonth" : "october",
        "taskSumissionStatus" : "yes",
        "task" : "weathe api"
}
{
        "_id" : ObjectId("632695f9637745c54e0fff3e"),
        "taskId" : 3,
        "taskTaughtMonth" : "october",
        "taskSumissionStatus" : "yes",
        "task" : "youtube clone"
}
{
        "_id" : ObjectId("632695f9637745c54e0fff3f"),
        "taskId" : 4,
        "taskTaughtMonth" : "october",
        "taskSumissionStatus" : "no",
        "task" : "netflix clone"
}
{
        "_id" : ObjectId("632695f9637745c54e0fff40"),
        "taskId" : 5,
        "taskTaughtMonth" : "october",
        "taskSumissionStatus" : "no",
        "task" : "cat api"
}
{
        "_id" : ObjectId("632695f9637745c54e0fff41"),
        "taskId" : 6,
        "taskTaughtMonth" : "october",
        "taskSumissionStatus" : "no",
        "task" : "school managment"
}
{
        "_id" : ObjectId("632695f9637745c54e0fff42"),
        "taskId" : 7,
        "taskTaughtMonth" : "october",
        "taskSumissionStatus" : "no",
        "task" : "shopping"
}
{
        "_id" : ObjectId("632695f9637745c54e0fff43"),
        "taskId" : 8,
        "taskTaughtMonth" : "october",
        "taskSumissionStatus" : "no",
        "task" : "ui design"
}
6.company_drives
db.companydrives.find().pretty()
{
        "_id" : ObjectId("632694c4637745c54e0fff34"),
        "companyDriveId" : 1,
        "companyDriveDate" : "15th oct",
        "noOfCompanyDriveAttended" : 2
}
{
        "_id" : ObjectId("632694c4637745c54e0fff35"),
        "companyDriveId" : 2,
        "companyDriveDate" : "16th oct",
        "noOfCompanyDriveAttended" : 2
}
{
        "_id" : ObjectId("632694c4637745c54e0fff36"),
        "companyDriveId" : 3,
        "companyDriveDate" : "21st oct",
        "noOfCompanyDriveAttended" : 2
}
{
        "_id" : ObjectId("632694c4637745c54e0fff37"),
        "companyDriveId" : 4,
        "companyDriveDate" : "22nd oct",
        "noOfCompanyDriveAttended" : 2
}
{
        "_id" : ObjectId("632694c4637745c54e0fff38"),
        "companyDriveId" : 5,
        "companyDriveDate" : "23rd oct",
        "noOfCompanyDriveAttended" : 2
}
{
        "_id" : ObjectId("632694c4637745c54e0fff39"),
        "companyDriveId" : 6,
        "companyDriveDate" : "27th oct",
        "noOfCompanyDriveAttended" : 2
}
{
        "_id" : ObjectId("632694c4637745c54e0fff3a"),
        "companyDriveId" : 7,
        "companyDriveDate" : "30th oct",
        "noOfCompanyDriveAttended" : 2
}
{
        "_id" : ObjectId("632694c4637745c54e0fff3b"),
        "companyDriveId" : 8,
        "companyDriveDate" : "31st oct",
        "noOfCompanyDriveAttended" : 2
}
7.mentors
db.mentors.find().pretty()
{
        "_id" : ObjectId("63268a5e637745c54e0fff0c"),
        "mentorId" : 1,
        "noOfMentorsAssigned" : 16
}
{
        "_id" : ObjectId("63268a5e637745c54e0fff0d"),
        "mentorId" : 2,
        "noOfMentorsAssigned" : 16
}
{
        "_id" : ObjectId("63268a5e637745c54e0fff0e"),
        "mentorId" : 3,
        "noOfMentorsAssigned" : 16
}
{
        "_id" : ObjectId("63268a5e637745c54e0fff0f"),
        "mentorId" : 4,
        "noOfMentorsAssigned" : 16
}
{
        "_id" : ObjectId("63268a5e637745c54e0fff10"),
        "mentorId" : 5,
        "noOfMentorsAssigned" : 13
}
{
        "_id" : ObjectId("63268a5e637745c54e0fff11"),
        "mentorId" : 6,
        "noOfMentorsAssigned" : 15
}
{
        "_id" : ObjectId("63268a5e637745c54e0fff12"),
        "mentorId" : 7,
        "noOfMentorsAssigned" : 12
}
{
        "_id" : ObjectId("63268a5e637745c54e0fff13"),
        "mentorId" : 8,
        "noOfMentorsAssigned" : 13
}
