# carfinance247

This project focuses on classifying car sale transcripts obtained from phone calls. 

Currently at Car Finance 247, after being automatically forwarded the transcripts, an API interprets both incoming and outgoing calls according to responses to 200 pre-defined questions.  

Despite this seemingly fluid system, its autonomous nature may not be optimal, especially within two specific call categories: Category 6 and Category 7 calls. Category 6 calls refer to introduction calls, where agents gather customer preferences and explain the intricacies of the loan application process. Conversely, category 7 calls are confirmation calls following completion of the loan agreement. 

Quality assurance and compliance are something that cannot be ignored in modern business. Currently, the classification process obtained via API relies on heuristics, which, while maintaining an impressive 80% accuracy rate, has an extremely low recall of 2%. This means that when the system does recognise a call it is highly accurate at classifying it, however, it often fails to recognise Category 6 and 7 calls completely. 

Missing these classifications can lead to gaps in compliance monitoring and hinder customer experience; thus, a new approach is required. 
