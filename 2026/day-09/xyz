# Create groups
groupadd developers
groupadd admins
groupadd project-team

# Create users
useradd -m tokyo
useradd -m berlin
useradd -m professor
useradd -m nairobi

# Add users to groups
usermod -aG developers tokyo
usermod -aG developers berlin
usermod -aG admins professor
usermod -aG admins berlin
usermod -aG project-team nairobi
usermod -aG project-team tokyo

# Create directories
mkdir /opt/dev-project
mkdir /opt/team-workspace

# Set group ownership
chown :developers /opt/dev-project
chown :project-team /opt/team-workspace

# Set permissions and enable setgid
chmod 775 /opt/dev-project
chmod 775 /opt/team-workspace

# Test access as users
sudo -u tokyo touch /opt/dev-project/tokyo.txt
sudo -u berlin touch /opt/dev-project/berlin.txt
sudo -u nairobi touch /opt/team-workspace/nairobi.txt
