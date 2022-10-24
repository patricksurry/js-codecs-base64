# js-codecs-base64

Experimenting with approaches for compressing integer data directly into
url safe base 64ish representations.

vlq uses variable length encoding into 64 bit chunks plus a run-length encoding mode

fib uses fibonacci coding with a selectable run-length encoding marker

zigzag/zagzig maps mixed signed integers into positive ones
