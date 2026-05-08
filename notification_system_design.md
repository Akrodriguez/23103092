# STAGE 1

The core actions the notification platform should suport are displaying notifications, Delete Notifications, reply to notifications. It uses REST APIs so basically CRUD operations.




# STAGE 2

I will prefer using MongoDB since its scalable and uses a JSON format which is key-value pair practice. 
If the data volume increases, the data might get overflowed and we could lose data.

# STAGE 3

This query is accurate as it searching for a specific student and the constraint set is isread = FALSE so all notifications which are not been opened by the student.
This query is slow since the large amount of data is not being handled correctly in the database system.

SELECT * FROM students, notificationTYPE
WHERE notification_type = 7 & Placement = TRUE
ORDER BY createdAt ASC;

