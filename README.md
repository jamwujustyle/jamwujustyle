[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zhamshid-abdulazizov)
```protobuf
syntax = "proto3";

package zhamshid;

/* * User: Zhamshid Abdulazizov
 * Role: Software Developer & Future Cloud Engineer
 */
message AboutMe {
  option (status) = LEARNING;
  option (created_at) = {
    year: 2001,
    month: June,
    day: 8
  };
  
  message Metadata {
    string name = "Zhamshid Abdulazizov";
    string origin = "Kazakhstan 🇰🇿";
    string location = "Uzbekistan 🇺🇿";
    repeated string languages = 3;
  }

  message TechStack {
    option (os_version) = 24.04 Noble Numbat; 
    repeated string backend = 1;  // ["Django", "FastAPI", "Go"]
    repeated string frontend = 2; // ["Next.js"]
    repeated string cloud = 3;    // ["PostgreSQL", "Docker", "AWS (In Progress)"]
  }

  enum WorkMode {
    EXTREME_OWNERSHIP = 0;
    PROACTIVE = 1;
    INDEPENDENT = 2;
  }
}
```
