# experiment_2
#html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 2 - Styled Profile</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="profile-container">
        <h1>Profile</h1>
        <div class="profile-content">
            <img id="profile-pic" src="e:/Arindam/1702735843535.jpg" alt="Profile Picture">
            <div class="info">
                <p><strong>Name:</strong> Arindam Konwar</p>
                <p><strong>Student ID:</strong> 2023202022108</p>
                <p><strong>Department:</strong> Computer Science and Engineering</p>
                <p><strong>Institute:</strong> Central Institute of Technology</p>
                <p><strong>Location:</strong> Kokrajhar, Assam</p>
            </div>
        </div>
    </div>
</body>
</html>
#css

body {
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
    color: #333;
    margin: 0;
    padding: 20px;
}


.profile-container {
    max-width: 800px;
    margin: 0 auto;
    background-color: #ffffff;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}


.profile-content {
    display: flex;
    align-items: flex-start;
    gap: 30px;
    margin-top: 20px;
}


#profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #2056e1;
}


h1 {
    color: #2056e1;
    text-align: center;
}


.info p {
    font-size: 18px;
    margin: 8px 0;
    line-height: 1.5;
}
