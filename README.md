# Classification of Japanese news with BERT_multi


BERT, or Bidirectional Encoder Representations from Transformers by Google, is a new method of pre-training language representations which obtains state-of-the-art results on a wide array of Natural Language Processing (NLP) tasks.

The academic paper by Google which describes BERT in detail and provides full results on a number of tasks can be found here: https://arxiv.org/abs/1810.04805.


I use “livedoor news corpus” (1) for this experiment.  The details of the experiment is explained in this blog.
https://toshistats.wordpress.com/2019/04/30/bert-performs-very-well-in-japanese-in-our-experiment/




### Evaluation results

test_accuracy = 0.8744,

finetuned with data of livedoor news corpus (training 3153 samples, test 826 samples)







(1) livedoor news corpus CC BY-ND 2.1 JP
https://creativecommons.org/licenses/by-nd/2.1/jp/



# THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
# IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
# FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
# AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
# LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
# OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
# THE SOFTWARE.

