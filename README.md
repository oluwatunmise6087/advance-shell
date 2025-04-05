# advance-shell

# Script to check CPU usage, memory usage, disk usage, and running processes.
 ![advance-shell1](advance-shell1.PNG)

# Make the script executable.
# Run the script to check system health.
chmod +x health_check.sh
./health_check.sh
![advance-shell2](advance-shell2.PNG)


# Schedule the script to run every hour using cron.
 crontab -e 
![advance-shell3](advance-shell3.PNG)

# Modify the script to send an email if CPU usage exceeds 90%
![modify-1](modify-1.PNG)