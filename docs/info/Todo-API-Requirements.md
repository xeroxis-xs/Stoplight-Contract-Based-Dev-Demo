---
stoplight-id: 9mqze2hbo5stt
tags: [info]
---

# Todo API


## Purpose
Todo API provides a simple way for users to manage their tasks and plan their day. This API can be used to create mobile and web applications.

## User Stories
- As a user, I want to create a task with name, description and whether is has been completed
- As a user, I want view the created tasks on my table
- As a user, I want to update the tasks the the details
- As a user, once the task is completed, I want to mark it as completed
- As a user, I want to delete the tasks that belongs to me if any mistakes have been made

## Data Model 
### Task Object
```json
{
  "id": 0,
  "name": "string",
  "description": "string",
  "completed_at": "datetime",
  "created_at": "datetime",
  "updated_at": "datetime"
}
```