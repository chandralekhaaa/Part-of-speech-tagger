# Part-of-speech-tagger

Project Description
<br/>As part of this project, a part of speech tagger was implemented using 2 statistical models - a Hidden Markov Model and a Recurrent Neural Network.

Dataset
<br/>A modified Brown corpus was used for training the model. The tagset contains the following tags - Noun, Pronoun, Verb, Adjective, Conjunction, Preposition, Determiner, Number, Punctuation and Other.

Tech stack
<ol>
<li>Python</li>
<li>Keras</li>
</ol>

Hidden Markov Model(HMM)
<br/>HMM is a statistical Markov model in which the system being modeled is assumed to be a Markov process with unobserved (hidden) states.

Implementation steps - Hidden Markov Model
<ol>
<li>Loading the data</li>
<li>Preprocessing the data</li>
<li>Initialising initial tag probabilities,transition probabilities and emission probabilities</li>
<li>Training the model using Viterbi Algorithm</li>
</ol>

Recurrent Neural Network
<br/>Recurrent Neural Network(RNN) is a type of Neural Network where the output from the previous step are fed as input to the current step. 

Implementation steps - Recurrent Neural Network
<ol>
<li>Loading the data</li>
<li>Transforming the data to feed to the RNN</li>
<li>Defining the model. An Embedding layer, an LSTM layer with a Bidirectional modifier and a Dense layer were used in the model.</li>
<li>Training the model</li>
<li>Testing and evaluating the model</li>
</ol>

Resources
<br/>Keras - https://keras.io/api/
<br/>Viterbi Algorithm - https://en.wikipedia.org/wiki/Viterbi_algorithm

