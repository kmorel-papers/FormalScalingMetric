cmake_minimum_required(VERSION 2.8)

project(FormalScalingMetric NONE)

include(UseLATEX.cmake)

add_latex_document(FormalScalingMetric.tex
  DEFAULT_PDF
  )
