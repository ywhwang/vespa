# Copyright 2017 Yahoo Holdings. Licensed under the terms of the Apache 2.0 license. See LICENSE in the project root.
vespa_add_library(eval_eval_llvm OBJECT
    SOURCES
    compile_cache.cpp
    compiled_function.cpp
    deinline_forest.cpp
    llvm_wrapper.cpp
)
