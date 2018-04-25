# tip mining
The success of developer question and answer (Q&A) websites attracts massive user-generated content for using and learning APIs, which easily leads to information overload: many questions related APIs have a large number of answers that can contain useful information and irrelevant one, and also cannot all be consumed by developers. In this work, we develop DeepTip, a novel deep learning based approach that uses a Convolutional Neural Network (CNN) to extract short practical and useful tips from developer answers for using or learning APIs. The results of extensive empirical experiments prove that DeepTip can extract useful tips from a large corpus of answers to questions with a high precision (i.e., 0.827) and a high AUC (i.e., 0.872), and it outperforms one state-of-the-art approach by up to 146.7% in terms of precision. Furthermore, qualitatively, a use study is conducted by different level of web developers and its results confirm that tip extraction is useful and our approach generates high-quality tips from real SO developers’ perspectives.


parse.py - use frequenly used PHP methods to narrow down PHP posts
guides_extract.py - create templates
cand.py - create tip candidates

<b>under dataset folder, they are our dateset in this research</b>

para_tip.pos - labelled paragraph level tip
para_tip.neg - non tips

sent_tip.pos - labelled sentence level tip
sent_tip.neg - non tips

sise_fs.py - create baseline features
sise_clf.py - baseline classification

deeptip_fs.py - create features for DEEPTip-F
deeptip_clf.py - DEEPTip-F classification

deeptip_w2v.py - DEEPTip-W2V
shcnn_seq2_bown.py - DEEPTip-OH
shcnn_3unsemb.py - DEEPTip-SEMI
