# Carleton University Official HyperK Collaboration Files #

### Purpose ###
The purpose of this repo is to organize parts and assemblies in a way which makes collaborating designers confident that they are using the latest and accurate models in their own designs. This is especially important as we standardize parts that we intend to order in mass quantity. 

### Implementation ###
To avoid jumbled piles of files, a directory will be created for each version of each part, and each assembly. This does create a relatively "tall" file structure, but it removes any need to think about where files might be, or where they should go. Related files go with their respective part.

To make things as easy as possible markdown template files are used to create an easy web-viewable description for each part and assembly. When combined with github's version history it should be simple to make corrections to these descriptions and share new model versions.

In addition, ``.STEP`` files have been exported opposed to only proprietary files such as SolidWorks parts. Most modern CAD software can open SolidWorks files, but their assemblies are not self contained and are prone to missing dependencies and conversion errors. (In situations where it could be useful to get a source file a respective proprietary file should be also uploaded for users of that software.)
