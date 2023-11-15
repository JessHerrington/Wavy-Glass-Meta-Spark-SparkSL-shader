# Wavy-Glass-Meta-Spark-SparkSL-shader
A glass shader for use in Meta Spark software. It can be added to a material to create a glassy effect with reflections, refractions, and chromatic aberration. It also has vertex displacement component for a wobble effect. 

HOW TO USE THIS SHADER:
In Meta Spark Studio, add the script to a material as a shader asset. Some info on this process can be found here: https://spark.meta.com/learn/scripting/shader-code-asset#advanced-example  

You will see different input parameters appear within the Spark interface on the material for: tex (texture), reflectionIntensity, refractionIntensity, chromaticAberration, and vertexDisplacement.

Some good values to get started are:

reflectionIntensity = 0.5

refractionIntensty = 0.5

chromaticAberration = 3

vertexDisplacement = 0.002


Lastly, add the camera texture to the tex input parameter.

Enjoy! :)


