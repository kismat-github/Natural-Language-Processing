# Natural-Language-Processing
In [5]: import nltk
        texts = "I am the only person who can run this program too much efficiently."
        for text in texts:
      sentences = nltk.sent_tokenize(texts)
      for sentence in sentences:
        words = nltk.word_tokenize(sentence)
        tagged = nltk.pos_tag(words)
        print(tagged)
      for text in texts:
    words=nltk.word_tokenize(texts)
    for word in words:
        word
otput

[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
[('I', 'PRP'), ('am', 'VBP'), ('the', 'DT'), ('only', 'JJ'), ('person', 'NN'), ('who', 'WP'), ('can', 'MD'), ('run', 'VB'), ('this', 'DT'), ('program', 'NN'), ('too', 'RB'), ('much', 'JJ'), ('efficiently', 'RB'), ('.', '.')]
In [ ]:
​
