cc_test_old(
  ir_kernel_dialect_pass_test
  SRCS
  ir_kernel_dialect_pass_test.cc
  DEPS
  transform
  program_translator
  op_dialect
  pir
  phi
  gtest)
