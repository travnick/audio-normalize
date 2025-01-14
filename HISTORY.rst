.. :changelog:

History
-------

0.2.2 (2016-02-12)
__________________

* Fixed issue where ffmpeg could not be found if path included spaces

0.2.2 (2016-02-09)
__________________

* Change default level back to -26

0.2.1 (2016-02-08)
__________________

* Documentation fixes


0.2.0 (2016-02-08)
__________________

* Support multiple input files
* Allow merging with input file instead of creating separate WAV
* Write to directory instead of using prefix
* Set the audio codec when merging
* Set additional encoder or ffmpeg options

Note: avconv support is very limited, use the real ffmpeg from http://ffmpeg.org/ instead.

0.1.3 (2015-12-15)
__________________

* Bugfix for detecting ffmpeg or avconv on Windows (as .exe)
* Add version to Usage message
* Update year

0.1.2 (2015-11-13)
__________________

* Bugfix for missing ffmpeg or avconv


0.1.0 (2015-08-01)
__________________

* First release, changing name to ffmpeg-normalize
