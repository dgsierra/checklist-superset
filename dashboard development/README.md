Accessing the Checklick Themes in Apache Superset (locally)

  1. Open Docker Compose Desktop
     
  3. See localhost port
      - a) Run the code: docker compose ps
      - b) Read the PORTS column
      - c) E.g., 0.0.0.0:8088->8088/tcp means use http://localhost:8088
        
  4. Create a Superset account (if no account yet)
      - a) Run from the folder with docker-compose.yml
      - b) Create an admin user inside the running container
      
  7. Login (already have an account)
      - a) Open localhost in a browser
        
  9. Upload themes.zip file into Apache Superset
