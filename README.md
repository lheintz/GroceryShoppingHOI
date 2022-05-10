# Grocery Shopping Human Object Interaction
6.869 Computer Vision Final Project

## Contributors
Name: Lauren Heintz & Max Tanski

# Abstract
To understand a visual world, machines must be able to identify objects and determine the way these objects interact with each other.  However, these interactions are not trivial and at times can be quite complex.  In this paper we explore the dependent relationships between these objects in order to allow a machine to be able to recognize and classify the objects in an image that are acting and the objects that are the targets of these actions. Quite often, humans are at the center of such interactions.  Detecting these human-object interactions is an important practical and scientific problem that has application in many domains.  We hypothesize that the instance segmentation boundaries of current object detectors can be leveraged to identify both people and their actions is a powerful cue for localizing the objects they are interacting with. We propose an implementation to exploit this cue by creating a model that learns to predict a target object given assumed action based on the instance segmented pose of a detected person.

# Files

### Final Project

| Name | Type | Description |
| --- | --- | ---|
| toy_dataset | Folder | Contains all input images in our curated "Human in Supermarket" toy data set |
| src | Folder | Contains the analysis source code to create Branches A, B, C, D of the human object interaction pipeline  |
| results | Folder | Contains annotated image outputs of all branches of the pipeline |
| `6.869 Final Presentation.pdf` | File | 6.869 Deliverable |
| `6.869 Final Report.pdf` | File | 6.869 Deliverable |
| `README.md` | File | README for project repo. |
| `LICENSE.md` | File | License for project repo. |


# License

The license for this project can be found in the `LICENSE.md` file.
