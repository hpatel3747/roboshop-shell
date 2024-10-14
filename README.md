## roboshop-shell
deployment using bash script
### List of Functions created in common.sh
1. app_prerequisites
   - adds application user roboshop
   - creates application directory /app
   - download application content in /tmp
   - extracts application contect in /app
2. print_heading
   - color the text and appends in log file log_file
   - print on screen in color
3. systemd_setup
   - copy service file
   - load, enable and starts the service
4. nodejs_setup
   - disable default NodeJS
   - enable NodeJS 20
   - Install NodeJS
   - Install NodeJS dependencies
5. python_setup
   - Install python
   - checks app_prerequisites
   - runs systemd_setup
6. maven_setup
   - Install Maven
   - checks app_prerequisites
   - Download Application Dependencies
   - runs systemd_setup 
