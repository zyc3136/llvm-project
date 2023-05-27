add_llvm_component_library(LLVMObfuscation
  HelloWorld.cpp
  CryptoUtils.cpp


  DEPENDS
  intrinsics_gen

  LINK_COMPONENTS
  Core
  Support
  Analysis
  TransformUtils
  )