# AI_HACKING
Collection of CVE(work) on tenserflow binary pwning it

FOR CVE2022_23591(WHICH IS STILL UNDER WORK I NEED TO FIGURE OUT HOW TO TURN BACK JSON TO PROTOBUF AND THAN DO

with tf.io.gfile.GFile('test.pb', 'rb') as f:
  graph_def = tf.compat.v1.GraphDef()
  print("aiciaaaaaaaaaaaaaa")
  print(graph_def)
  graph_def.ParseFromString(f.read())
  #tf.saved_model.load('/tmp/saved_model')

)
