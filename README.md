# Bugs.jar: A Large-scale, Diverse Dataset of Bugs for Java Program Repair

## Directory & File Structure
To browse a specific bug data, please go to one of the following project directories and select a branch starting with "bugs-dot-jar-".  The branch names follow the format: "bugs-dot-jar\_\[JIRA Issue ID\]\_\[Git commit ID of the fixed version\].  Each branch in a project represents the buggy version corresponding to the JIRA Issue and also includes the developer patch and the test results under `.bugs-dot-jar` directory.
```
.
+-- accumulo
|   +-- .bugs-dot-jar
|       +-- developer-patch.diff
|       +-- test-results.txt
|       +-- flaky-test-results.txt
+-- camel
|   +-- ...
+-- commons-math
|   +-- ...
+-- flink
|   +-- ...
+-- jackrabbit-oak
|   +-- ...
+-- logging-log4j2
|   +-- ...
+-- maven
|   +-- ...
+-- wicket
|   +-- ...
+-- README.md
+-- .gitmodules
```

## Disclamer
THIS SOFTWARE DATA SET IS PROVIDED BY THE COPYRIGHT HOLDER AND CONTRIBUTOR "AS IS." BY USING THE SOFTWARE DATA SET, YOU EXPRESSLY UNDERSTAND AND AGREE THAT, EXCEPT TO THE EXTENT PROHIBITED BY LAW, ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE, AND/OR ANY WARRANTIES THAT THIS SOFTWARE DATA SET WILL BE ERROR FREE OR FREE OF HARMFUL COMPONENTS, ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE DATA SET, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

You understand and agree that you will not: 1) make false or misleading statements or representations regarding Fujitsu or Fujitsu products and services; 2) take on any obligation or responsibility, or make any representation, warranty, guarantee or endorsement to anyone on Fujitsu’s behalf (including, without limitation, any of our products or services); and that you will not state or imply that Fujitsu has developed, endorsed, reviewed or otherwise approved of any of your products.  You agree that you will indemnify, defend and hold us harmless from and against any and all claims which may arise under or out of your use of the Software Data Set; your negligence or intentional misconduct; your products, or any integrations you develop, design, promote or distribute using the Software Data Set; any misrepresentations you make with respect to Fujitsu, or Fujitsu products or services.
