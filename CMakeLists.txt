cmake_minimum_required(VERSION 2.8)

project(FormalScalingMetric NONE)

include(UseLATEX.cmake)

set(image_src
  images/HabibTime.pdf
  images/HabibTimePerParticle.pdf
  images/HabibRate.pdf
  images/HabibEfficiency.pdf
  images/OldfieldTimeLinear.pdf
  images/OldfieldTimeLog.pdf
  images/OldfieldRate.pdf
  images/OldfieldEfficiency.pdf
  )

add_latex_document(FormalScalingMetric.tex
  BIBFILES FormalScalingMetric.bib
  IMAGES ${image_src}
  DEFAULT_PDF
  )
