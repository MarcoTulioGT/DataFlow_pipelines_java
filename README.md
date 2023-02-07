# DataFlow_pipelines_java

cd $BASE_DIR
# Set up environment variables
export MAIN_CLASS_NAME=com.mypackage.pipeline.MyPipeline
mvn compile exec:java \
-Dexec.mainClass=${MAIN_CLASS_NAME}
