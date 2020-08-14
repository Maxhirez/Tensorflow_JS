# Tensorflow_JS
 Personal experiments with Tensorflow JS
 
The BERT Demo application is a shell for the Tensorflow QNA module.  It allows a user to experiment with the <h3>Bidirectional Encoder Representations from Transformers</h3> model, a method of pre-training language representations which obtains state-of-the-art results on a wide array of Natural Language Processing tasks.(See github repository <a href="https://github.com/tensorflow/tfjs-models/tree/master/qna">here</a>.)
 
The application runs in the browser but for simplicity's sake uses Tensorflow libraries from a CDN, which results in several "hits" to the CDN server.  A typical Question/Answer set will take 2+ minutes and result in ~100Mb of web traffic.  This might be alleviated with local installation of the TF libraries but the application was developed as a preliminary evaluation tool.

To use, clone or download and open in a browser with an active web connection, then follow the directions on the page.  Firewalls and some VPNs are known to interfere.
