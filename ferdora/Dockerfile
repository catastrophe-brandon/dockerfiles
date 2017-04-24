
# Set the base image to Ubuntu
FROM fedora:latest

# Update the repository sources list
RUN \
	dnf -y group install workstation-product-environment && \ 
    systemctl set-default graphical.target && \
    systemctl enable gdm.service

# Expose the default port
EXPOSE 5000
