cmake_minimum_required(VERSION 3.16.3)

try_run(LIBRARY_MAGIC_VAL_RUN_RESULT
    LIBRARY_MAGIC_VAL_COMPILE_RESULT
    ${/root/.jenkins/workspace/now}/12c++
    "12c++.cpp"
    RUN_OUTPUT_VARIABLE LIBRARY_MAGIC_VAL_OUTPUT)
