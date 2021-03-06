Operator lists
==============

.. Please keep in chronological order when editing
.. csv-table::
    :header: "Operator","Supported","Remark"

    "AVERAGE_POOL_2D","Y",""
    "ARGMAX","Y","Only CPU and tensorflow is supported"
    "BATCH_NORM","Y","Fusion with activation is supported"
    "BATCH_TO_SPACE_ND","Y",""
    "BIAS_ADD","Y",""
    "CAST","Y","Only CPU and tensorflow model is supported"
    "CHANNEL_SHUFFLE","Y",""
    "CONCATENATION","Y","Only support channel axis concatenation"
    "CONV_2D","Y","Fusion with BN and activation layer is supported"
    "DECONV_2D","Y","Only tensorflow model is supported"
    "DEPTHWISE_CONV_2D","Y","Only multiplier = 1 is supported; Fusion is supported"
    "DEPTH_TO_SPACE","Y",""
    "DEQUANTIZE","Y","Model quantization will be supported later"
    "ELEMENT_WISE","Y","ADD/MUL/DIV/MIN/MAX/NEG/ABS/SQR_DIFF/POW/RSQRT/EQUAL"
    "EMBEDDING_LOOKUP","Y","Only support channel axis concatenation"
    "FULLY_CONNECTED","Y",""
    "GROUP_CONV_2D","","Caffe model with group count = channel count is supported"
    "IDENTITY","Y","Only tensorflow model is supported"
    "LOCAL_RESPONSE_NORMALIZATION","Y",""
    "LOGISTIC","Y",""
    "LSTM","",""
    "MATMUL","Y","Only CPU is supported"
    "MAX_POOL_2D","Y",""
    "PAD","Y",""
    "PSROI_ALIGN","Y",""
    "PRELU","Y","Only caffe model is supported"
    "REDUCE_MEAN","Y","Only tensorflow model is supported. For GPU only H + W axis reduce is supported"
    "RELU","Y",""
    "RELU1","Y",""
    "RELU6","Y",""
    "RELUX","Y",""
    "RESHAPE","Y","Limited support: GPU is full supported, for CPU only supports softmax-like usage"
    "RESIZE_BILINEAR","Y",""
    "RNN","",""
    "RPN_PROPOSAL_LAYER","Y",""
    "SHAPE","Y","Only CPU and tensorflow is supported"
    "STACK","Y","Only CPU and tensorflow is supported"
    "STRIDEDSLICE","Y","Only CPU and tensorflow is supported"
    "SLICE","Y","In tensorflow, this op is equivalent to SPLIT; Only support channel axis slice"
    "SOFTMAX","Y",""
    "SPACE_TO_BATCH_ND", "Y",""
    "SPACE_TO_DEPTH","Y",""
    "SQEEZE","Y","Only CPU and tensorflow is supported"
    "TANH","Y",""
    "TRANSPOSE","Y","Only CPU and tensorflow is supported"
