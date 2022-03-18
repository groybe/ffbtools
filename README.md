Quick fix for OpenFFBoard.
Possibly only works for constant force. Changes direction based on positive or negative value of constant force.
Wrongly sets duration of infinite effects as 0xFFFF although it does work. See https://github.com/berarma/ffbtools/issues/26#issuecomment-1070876603

Run with

`ffbtools-master/bin/ffbwrap --direction-fix --overwrite-length /dev/input/by-id/usb-Open_FFBoard_FFBoard_*event-joystick -- wine`
__________________________
# FFBTools

This is a set of evolving tools and documentation to help understand and debug
the FFB capabilities in GNU/Linux systems.

The goal for this project is to raise awareness of issues in FFB, specially for
steering wheels, help diagnose them and help more people get involved on fixing
them and collaborate on related projects. It can also be used as a learning
tool.

Please, read the complete documentation in the [docs](docs/README.md)
directory.

## Contributing

This project's goal isn't creating new software but creating knowledge, thus
new issues can be created to ask, discuss and talk about anything related to
FFB support on Linux. Just try to keep one topic per issue, please. We hope to
bring together anyone working on FFB related projects or willing to collaborate
on them so they can find help and suppport.

## Disclaimer

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
