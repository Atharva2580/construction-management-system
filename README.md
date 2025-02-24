# construction-management-system
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Construction Management System</title>
</head>
<body>

  <div class="container">
        <h1> Construction Management System</h1>
     <div class="project-form">
            <input type="text" id="projectName" placeholder="Enter project name">
            <select id="projectStatus">
                <option value="In Progress">In Progress</option>
                <option value="Completed">Completed</option>
            </select>
            <button onclick="addProject()">Add Project</button>
        </div>

   <table>
            <thead>
                <tr>
                    <th>#</th>
                    <th>Project Name</th>
                    <th>Status</th>
                    <th>Action</th>
                </tr>
            </thead>
            <tbody id="projectList"></tbody>
        </table>
    </div>

   <script src="script.js"></script>

</body>
</html>
