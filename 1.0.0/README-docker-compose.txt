
If time allows, Potential to try docker-compose:
Note:  git clone steps may already have been performed and need NOT be repeated!

1)   MacOS instructions:
cd
git clone https://github.com/NCAR/bww-ubc-class
cd  ./bww-ubc-class/1.0.0/
docker-compose up
docker run --rm -it -v ~/bww-ubc-class/1.0.0/ubc_wrfout/ubc_run1_np2:/wrfoutput bigwxwrf/ncar-ncl

2) Windows instructions:
cd \
git clone https://github.com/NCAR/bww-ubc-class
cd c:\bww-ubc-class\1.0.0
docker-compose -f docker-compose-windows.yml up
docker run --rm -it -v c:\bww-ubc-class\1.0.0\ubc_wrfout\ubc_run1_np2:/wrfoutput bigwxwrf/ncar-ncl
