cc_library(layer SRCS layer.cc DEPS proto_desc operator)
cc_library(tracer SRCS tracer.cc DEPS proto_desc)
cc_library(engine SRCS engine.cc)