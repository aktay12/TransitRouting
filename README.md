This project contains sample files to run your own test OpenTripPlanner2 instance for routing in Baltimore.
The map file is too large to include here, so it is available at this google drive link:
https://drive.google.com/file/d/1EjvHUi54WgmbYlavc7bw4Ns7JEgTp6or/view
Please include the configuration filesand map file in the github alongside the otp application (which can be downloaded from their website: 
https://docs.opentripplanner.org/en/latest/

Then, follow instructions in the OTP2 basic tutorial to start an instance from an existing map. You should have to use a line of code similar to this in command line:
java -Xmx2G -jar otp-shaded-2.7.0.jar --load .

Sinan Aktay, MS3 at University of Maryland School of Medicine. Please cite this GitHub and OpenTripPlanner2 if used in a manuscript.
