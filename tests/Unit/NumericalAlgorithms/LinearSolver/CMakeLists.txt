# Distributed under the MIT License.
# See LICENSE.txt for details.

set(LIBRARY "Test_LinearSolver")

set(LIBRARY_SOURCES
  Test_Lapack.cpp
  )

add_test_library(
  ${LIBRARY}
  "NumericalAlgorithms/LinearSolver/"
  "${LIBRARY_SOURCES}"
  "Convergence;DataStructures;LinearSolver"
  )
