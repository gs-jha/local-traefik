
FROM nginx

# Install fail2ban
RUN apt-get update && apt-get install -y fail2ban

# Copy fail2ban configuration file
#COPY fail2ban/jail.local /etc/fail2ban/

# Copy Nginx configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Copy mime.types file
COPY mime.types /etc/nginx/mime.types

# Expose ports
EXPOSE 80
EXPOSE 443
