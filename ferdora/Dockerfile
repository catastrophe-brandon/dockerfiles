
# Set the base image to fedora's latest
FROM fedora:latest

# Install stuff required for a GUI
RUN \
	dnf -y group install workstation-product-environment && \ 
    systemctl set-default graphical.target && \
    systemctl enable gdm.service

# Expose the default port
EXPOSE 5000
