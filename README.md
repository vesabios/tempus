# T E M P V S

<img src="img/tempusA.jpeg">


A clock and solar calendar screensaver.

Version 0.91 Beta </br>
© 2018-2021 S. Mason, All rights reserved.</br>
@vesabios on Twitter</br>

MacOS 10.9+ and Windows (only tested on windows 10, might work on others)

## Download 

<a id="raw-url" href="https://github.com/vesabios/tempus/blob/main/Release/Tempus.saver.zip?raw=true">Click here for the MacOS version</a>
<br>

<a id="raw-url" href="https://github.com/vesabios/tempus/blob/main/Release/Tempus_0.91.msi?raw=true">Click here for the Windows version</a>


## Presentation 

- The clock is a straightfoward 12-hour clock.
- The outer ring is a representation of the solar year. It is oriented such that the winter solstice is at the top, the summer solstice is at the bottom, and the equinoxes are on the sides. The ring will periodically zoom in and out to show you the current day within the month, shown as a triangular dial indicator. 
- The red dial in the middle shows an approximation of the earth. The center represents the configured latitude and longitude location. The yellow circle represents the sun and its orientation represents its position in the sky. The sun travels around the sphere as the day progresses, and its shadow can be seen in the visualization.
- Enter your latitude and longitude to configure it for your geographic location. It comes pre-configured for San Francisco. (Note that this does not currently take into account DST.)
- Quarter and cross-quarter days (e.g. solstices, equinoxes) are shown around he interior. You can toggle between an alternate set of names for these, derived from ancient european names.
- The calendar year is drawn using a solar year  of 365.25 days, with the winter solstice always being at the 12 position. 
- The yellow line represents the calendar new year - January 1.
- The end of the year and the beginning of the year will not match up perfectly on the calendar wheel, with about an extra quarter day's worth of space. That's expected - this gap represents the extra time we have at the end of each year. Cumulatively, this adds up to a whole day every four years. Thus, leap years.

<img src="img/tempusB.jpg">


## Software

This software was written in C++ using <a href="https://libcinder.org/">Cinder</a>. It was written sporadically over a period of many years. 


### MacOS
Runs on MacOS Version 10.9 (Mavericks) or higher. 

To install, open Tempus.saver by double clicking. It should install automatically, but you'll need to open up System Preferences and set it as your default screensaver for it to work.


### Windows
There is now a version for Windows as well. It's only been tested on Windows 10 so far.

To install, download the .msi file and double click on it. The extremely simple installed should copy it to your windows system32 or equivalent folder, which you don't need to worry about. To enable it, go do your display preferences and find the screen saver settings. NOTE: For some reason it doesn't render a preview in the little preview window, it just shows black. 

<br>

If you have trouble using it or installing it, I'm sorry!

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE COPYRIGHT HOLDERS OR ANYONE DISTRIBUTING THE SOFTWARE BE LIABLE FOR ANY DAMAGES OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

