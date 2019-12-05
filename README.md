# tornado-relayers-contest

We are launching a relayer's contest on @kovantestnet.
If you would like to be listed in tornado.cash UI relayer's dropdown option, please do the following:
1. Setup tornado.cash relayer node https://github.com/tornadocash/relayer/releases/tag/2.0
2. Setup ENS subdomain(kovan.****.eth) with TEXT record and URL key that points to your DNS or IP address.
3. Send a transaction to RelayersContest contract [contest.tornadocash.eth](https://etherscan.io/address/0x5f556365926f95f0d4cd80333c23d318b4b5a77a#writeContract) on mainnet by calling a `register` function with your ENS name as a parameter.
4. Test your relayer setup at https://stage.tornado.cash by choosing custom relayer's option.

Registration ends on December 10 5:00 AM UTC
Contest starts as soon as the registration ends
Contest ends on December 13 5:00 AM UTC

Please choose your testnet relayer's fee wisely as you would for the mainnet.

If your node responds to all requests and sustains all DDoS attacks, you might just win the contest.

Disclaimer: Please consult with legal and tax advisors regarding the compliance of running a relayer service in your jurisdiction. The authors of this project bear no responsibility.

USE AT YOUR OWN RISK.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
