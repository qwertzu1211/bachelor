# Bachelorarbeit
Die vorliegende Bachelorarbeit in Kooperation mit der Deutsche Sporthochschule Köln hat die Konzeption und Entwicklung eine Software, mit der Daten aus der Fußball-Bundeliga 2011–2012 mit Hilfe einer Heatmap erzeugt werden, zum Inhalt. Die Software soll die Torpositionen vor einem Offensivspiel zu verschiedenen Zeitpunkten des Spieles veranschaulichen. Bei der Arbeit wurden zwei Cluster-Methoden betrachtet, nämlich die Density-Based Spatial Clustering of Applications with Noise (DBSCAN) und der Kerndichtschätzer (kernel density estimation). DBSCAN ist ein bekannter Cluster-Algorithmus und wurde mit dem Software-Tool WEKA untersucht. Es zeigte sich, dass dieses Verfahren nicht so gut für diese Aufgabenstellung geeignet ist, da einzelnen Cluster nicht so gut unterschieden werden konnten. Der Kerndichtschätzer ist dagegen ein statistisches Verfahren zur Schätzung einer Dichte, der auch in Geoinformationssystemen verwendet wird. Dieses Verfahren ist besser für die Aufgabenstellung geeignet. Nach der Analyse der Daten im XML-Format wurde der Algorithmus Kerndichtschätzer für die Deutsche Sporthochschule Köln in detr Programmiersprache Java implementiert. Die Software untersucht die Bildung von Clustern bzw. die Torschussdichte mit der Absicht, ein Verhalten oder Muster vor einem Offensivspiel zu erkennen. Sie enthält eine sehr gute Visulisierung der verschiedenen Situationen, die zum Torschuss führten, anhand eines Fußballfeldes

https://epb.bibl.th-koeln.de/frontdoor/index/index/docId/992
