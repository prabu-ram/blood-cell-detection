# blood-cell-detection

A complete blood count (CBC) is a group
of tests (test panel) that gives information
about the cells and cell count in a patient's
blood. Earlier cell counting in a patient's
blood was performed manually, by viewing a
slide of the patient's blood sample under a
microscope. Nowadays, this process is
generally computerized which is done by
using an automated analyzer, and only
10-20% (approximately) of samples are
manually examined.
Abnormally high or low
counts may indicate the presence of many
forms of disease or illness, and hence blood
counts are mostly preferred to analyze the
blood cells, as they can provide us with a
rundown of a patient's general wellness.
In this Letter, a deep learning-based blood
cell counting method has been proposed. We
employ a deep learning-based object detection
method to detect different blood cells. Among the
state-of-the-art object detection algorithms and
methods such as regions with convolutional neural
network (R-CNN) and You Only Look Once
(YOLO), Single-shot Detectors (SSDs), we
choose SSD framework with VGG-16
architecture. We retrain the SSD framework to
automatically identify and count RBCs, WBCs,
and platelets from blood smear images.
