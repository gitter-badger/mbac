## Roadmap

**Deep analyse your motility assays and get more information out of them!**

MBac comprises software tools and an optional low-cost hardware setup for bacterial motility determination. The analysis is picture based and can either be used for end point determination or for monitoring bacteria swarming on agar plates. The software can determine various parameters like shape migration speed, migration direction or shape formation which usually are hard to determine in common motility assays. An optional lighting chamber can be 3D printed and equipped with single-board computer and a camera to perform on-line motility measurements and analysis.  

### What has to be done?

Here you see the project roadmap with open and completed milestones.


#### Milestone: Build first version of a lighting chamber with camera
Having a proper lighting chamber is very important for picture quality.

- Design a lid with slot for camera
- Design a main body for dark field lighting a plate. Inspired by "A bucket of light" from John S. Parkinson [(2007)](http://chemotaxis.biology.utah.edu/Parkinson_Lab/publications/PDFs/Parkinson,%202007b.pdf)
- Test the setup, create a time-lapse video and put it on YouTube

#### Milestone: Release of first software version
This should be a simple first version of the software without GUI or anything like that. It should be able to analyse at least two parameters from the pictures: migration area and migration speed over time.
- Detection of agar plate and inoculation site
- Image segmentation to identify migration area
- Migration area and speed over time from picture series

#### Milestone: Mozilla's Global Sprint (10.-12.05.2018)
**Deadline: 09.05.2018**
