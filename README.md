# MinGW on Docker

# Build Image
docker build --tag mingw .

# Run
1.change ./mingw bash script (specially env & mount options)
2. execute "mingw" with args

# Example OpenCV:
~/Workspace/C/library/OpenCV$ mingw ./build.sh mingw32-win32 4.3.0 Release

# Example Qt 5.6.3:
~$mingw-kit 5.6 windows 32 gcc release /home/hossein/Workspace/C/qt/kits src/5.6/5.6.3.zip

# Example LimeReport:
~/Workspace/C/qt/library/LimeReport/1.4.135$mingw qbuild.sh -p limereport.pro

# Example Daneshvar Project:
~/Workspace/C/qt/daneshvar$mingw qbuild.sh -p src/daneshvar.pro

# Example Atlas Project:
~/Workspace/Projects/araax/atlas$mingw qbuild.sh -p src/atlas.pro

# Example Sabta Project:
~/Workspace/Projects/araax/sabta$mingw qbuild.sh -p src/sabta.pro
