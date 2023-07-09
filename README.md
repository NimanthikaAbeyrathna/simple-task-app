
# simple-task-app

"simple-task-app is a user-friendly and efficient task management app that helps you stay organized and productive. With its intuitive interface, you can easily create your tasks."

#### Used tech stacks
1. Node JS
3. MySQL 
4. Angular

## version 
1.0.0
## Authors

- @nimanthikaabeyrathna


## 🚀 About Me
I'm a full stack developer...


## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nimanthika-abeyrathna-b27b48184/)
email - nimanthikaabeyrathna@gmail.com



## API Reference

#### Get all tasks

```http
  GET /app/api/v1/tasks
```


#### save task

```http
  POST /app/api/v1/tasks
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `description`| `string` | **Required**|
| `status`      | `enum('COMPLETED','NOT_COMPLETED` | |

#### delete task

```http
  DELETE /app/api/v1/tasks/:taskId
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`| `int` | **Required**|


#### update task

```http
  PATCH /app/api/v1/tasks/:taskId
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`| `int` | **Required**|
| `status`| `enum('COMPLETED','NOT_COMPLETED` | **Required**|



