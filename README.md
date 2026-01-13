/* General Styles */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

/* Header Styles */
.header {
    background: linear-gradient(135deg, #4caf50, #81c784);
    padding: 80px 20px 50px;
    position: relative;
}

.header .profile-img img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border: 5px solid white;
}

/* About Section */
#about {
    padding: 60px 20px;
}

/* Skills Section */
.skill-card {
    background: #fff;
    border-radius: 10px;
    padding: 20px;
    font-weight: bold;
    box-shadow: 2px 2px 8px rgba(0,0,0,0.2);
    transition: transform 0.3s, background-color 0.3s;
    cursor: default;
}

.skill-card:hover {
    transform: scale(1.05);
    background-color: #4caf50;
    color: white;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
}
