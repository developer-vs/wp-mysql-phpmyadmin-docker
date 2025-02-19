# 🚀 Start all services in detached mode (background)
docker compose up -d  

# ❌ Stop and remove containers, including volumes (use with caution!)
docker compose down --volumes  

# 📜 View logs for the WordPress container
docker compose logs wordpress  

# 🔍 Access a running container (replace '77' with actual container ID or name)
docker exec -it 77 /bin/bash  

# 🔄 Update package lists on Linux
sudo apt update  

# 📦 Install MySQL client (needed to connect to MySQL databases)
sudo apt install mysql-client  

# ✅ Verify MySQL client installation
mysql --version  

# 🔗 Connect to the MySQL database inside the container
# Replace credentials and database name as needed
mysql -h 127.0.0.1 -P 3306 -u wordpress_user -pSecureUserPass456! my_site  
