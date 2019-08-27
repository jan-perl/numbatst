# numbatst


This workbook runs the same code several times, and times the result

    interpreted python
    compiled cuda python 1 CPU core
    compiled cuda python all CPU cores
    compiled cuda python GPU, vectorize

    compiled cuda python GPU, guvectorize, or njit current vector size uses 12 Gb in total

    The interpreted python is run on a smaller sample, in order to reduce run times the vectorise version can only process 1/10 of the data, as all needs to be stored on the GPU. My GPU only as 2Gb memory, so vectorize does not work for this sample data


