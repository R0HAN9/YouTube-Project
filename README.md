# YouTube Project 
<strong>YouTube Backend</strong> is a Spring Boot-powered backend application designed to support a YouTube-like platform. 
It offers advanced features such as video recommendations, content moderation, targeted advertising, and a robust CRUD API. 
Built using MongoDB for efficient data management, this project is optimized for scalability, modularity, and clean architecture, 
ensuring seamless integration with frontend systems.

### Features
<ul>
    <li><strong>Video Recommendations:</strong> Personalized suggestions based on user preferences.</li>
    <li><strong>Content Moderation:</strong> Automatic filtering of inappropriate or restricted content.</li>
    <li><strong>Ad Targeting:</strong> Customizable ad placement tailored to user demographics.</li>
    <li><strong>CRUD API:</strong> Full support for managing videos, users, and other resources.</li>
</ul>

<h2>Project Structure</h2>
<pre>
YouTubeBackend/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── youtube/
│   │   │           ├── YouTubeApplication.java  # Main Application Class
│   │   │           ├── config/                 # Configuration Classes
│   │   │           ├── controller/             # REST Controllers
│   │   │           ├── service/                # Business Logic Layer
│   │   │           ├── repository/             # MongoDB Repositories
│   │   │           ├── dto/                    # Data Transfer Objects
│   │   │           ├── model/                  # Entity Classes
│   │   │           └── util/                   # Utility Classes
│   │   ├── resources/
│   │   │   ├── application.properties          # Application Configurations
│   │   │   └── static/                         # Static Resources
├── pom.xml                                     # Maven Dependencies
└── README.md                                   # Project Documentation
</pre>
