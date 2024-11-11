<link rel="stylesheet" href="styles/home.css">
<link rel="stylesheet" href="styles/about.css">
<!-- Add more as needed -->

<link rel="stylesheet" href="styles/main.css">

.profile-pic {
    border-radius: 50%;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.about-me {
    font-family: 'Roboto', sans-serif;
    line-height: 1.6;
    margin: 20px;
}

.resume-section {
    background: #f9f9f9;
    padding: 20px;
    border-radius: 8px;
}

.project {
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 15px;
    margin-bottom: 20px;
}

.contact-form input, .contact-form textarea {
    border: 1px solid #ccc;
    padding: 10px;
    border-radius: 4px;
}

a:hover {
    color: #007bff;
    text-decoration: underline;
}
.button {
    background-color: #007bff;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.button:hover {
    background-color: #0056b3;
}

.image {
    border-radius: 8px;
    transition: transform 0.3s ease;
}

.image:hover {
    transform: scale(1.05);
}

@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
    .sidebar {
        display: none;
    }
}

body {
    font-family: 'Open Sans', sans-serif;
    font-size: 16px;
    line-height: 1.6;
}

h1, h2, h3 {
    font-family: 'Roboto', sans-serif;
}

button:focus {
    outline: 2px solid #0056b3;
}

a:active {
    color: #003d80;
}

.flex-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.card {
    transition: transform 0.3s ease;
}

.card:hover {
    transform: scale(1.05);
}

@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

.fade-in {
    animation: fadeIn 2s ease-out;
}
