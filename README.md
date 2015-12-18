# IR-project
This project is about building a system that can extract text from a collection of Arabic books and build an index and search engine for investigating these texts.

#USING
* natural language processing
* machine learning
#Goal
* find relationships among  arabic books

#allowable
*to use extra metadata for each text to help help researchers in their analysis of these texts (such as author, date, etc.).

#example
the system may allow the users to investigate things such as:
*      Full text search for phrases.
*      Classification or clustering of books based on their content.
*      Discover relationships among texts, based on quotations and similarity analysis.
*      Visualize these findings using innovative charts (similar to D3.js interactive charts).
------------------------------------------------------------------------------------------------

 A)Training


+----------+
|----------|                                                        +-----------+
|| Arabic ||                            +-----------+               |           |
|| Books  ||     Input                  |           |               | Machine   |
|---------------------------------------> Feature   +-------------->+ Learning  |
||        ||                            | Extractor |               | Algorithm |
||        ||                            |           |               |           |
||        ||                            +-----------+               |           |
|----------|                                                        +------+----+
+----------+                                                               |
                                                                           |
                                                                           |
                                                                           |
                                                                           |
 B)Prediction                                                              |
                                                                           v
                                                                    +------+------+
                                                                    |             |
+----------+                                                        |             |
|----------|                                                        |             |
|| Arabic ||                            +-----------+               | Classifier  |
|| Books  ||     Input                  |           |               |             |
|---------------------------------------> Feature   +-------------->+    Model    +---->
||        ||                            | Extractor |               |             |
||        ||                            |           |               |             |
||        ||                            +-----------+               |             |
|----------|                                                        |             |
+----------+                                                        +-------------+
------------------------------------------------------------------------------------------------------


