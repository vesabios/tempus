# T E M P V S

A sidereal clock and calendar screensaver.

Version 0.9 Beta
© 2021 Steve Mason, All rights reserved.

## Software

This software was written in C++ using <a href="https://libcinder.org/">Cinder</a>. It was sporadically over a period of many years.

It is compiled for MacOS Version 10.9 or higher. There is a Windows version coming at some point.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE COPYRIGHT HOLDERS OR ANYONE DISTRIBUTING THE SOFTWARE BE LIABLE FOR ANY DAMAGES OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Presentation 

- The red dial in the middle shows the active daylight hours.  Enter your latitude and longitude below to configure it for your geographic location. (Note that this does not currently take into account DST.)
- Quarter and cross-quarter days like the solstices are shown around the interior. You can toggle between an alternate set of names for these.
- The calendar year is drawn using a solar year  of 365.25 days, with the winter solstice always being at the 12 position.  
- The end of the year and the beginning of the year will not match up perfectly on the calendar wheel, with about an extra quarter day's worth of space. That's expected - this gap represents the extra time we have at the end of each year. Cumulatively, this adds up to a whole day every four years. Thus, leap years.
