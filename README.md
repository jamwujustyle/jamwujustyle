```protobuf
syntax = "proto3";

package zhamshid;

/* * User: Zhamshid Abdulazizov
 * Role: Software Developer & Future Cloud Engineer
 */
message AboutMe {
  option (os_version) = 24.04 Noble Numbat; 
  option (status) = LEARNING;
  
  message Metadata {
    string name = "Zhamshid Abdulazizov";
    string origin = "Kazakhstan 🇰🇿";
    string location = "Uzbekistan 🇺🇿";
    repeated string languages = 3;
  }

  message TechStack {
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
