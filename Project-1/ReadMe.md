# Assignment 1B

## What are Channels and Kernels (according to EVA)?

As per session easy connection to remember for Kernels and Channels is:

KERNELS = FEATURE_EXTRACTOR

CHANNELS = SIMILAR_FEATURE_BAGS



**Kernel** 

* is a base most part that can be found in every input, kind of elemental part of the input. 

For eg. an Image is build with various edges and colors.



**Channels**

* are collection different version of features that essentially can be represented with same Kernel

For eg. Various versions of vertical edges features is a channel. 



## Why should we only (well mostly) use 3x3 Kernels?

There are various reasons to uses 3x3 Kernels only, based on institutive reasoning from sessions was have understood 2 reasons for that :

1. Processing with 3x3 Kernel is faster then other higher order Kernels
2. Also with 3x3 Kernel any other higher Kernels process can be achieved. 

Additionally, while reviewing some articles was able to understand that by keeping kernel size of 3x3 helps in following cases:

1. Learning common rules for different situations and generalize better
2. Allows to go deeper and make layers lighter

Referred articles:

* <https://stats.stackexchange.com/questions/222883/why-are-neural-networks-becoming-deeper-but-not-wider>
* <https://blog.sicara.com/about-convolutional-layer-convolution-kernel-9a7325d34f7d>



## How many times do we need to perform 3x3 convolution operation to reach 1x1 from 199x199 (show calculations)

We need 99 3x3 convolutions to reach 1x1 from 199x199; PFB grinding visualization:

199x199

197x197

195x195

193x193

191x191

189x189

187x187

185x185

183x183

181x181

179x179

177x177

175x175

173x173

171x171

169x169

167x167

165x165

163x163

161x161

159x159

157x157

155x155

153x153

151x151

149x149

147x147

145x145

143x143

141x141

139x139

137x137

135x135

133x133

131x131

129x129

127x127

125x125

123x123

121x121

119x119

117x117

115x115

113x113

111x111

109x109

107x107

105x105

103x103

101x101

99x99

97x97

95x95

93x93

91x91

89x89

87x87

85x85

83x83

81x81

79x79

77x77

75x75

73x73

71x71

69x69

67x67

65x65

63x63

61x61

59x59

57x57

55x55

53x53

51x51

49x49

47x47

45x45

43x43

41x41

39x39

37x37

35x35

33x33

31x31

29x29

27x27

25x25

23x23

21x21

19x19

17x17

15x15

13x13

11x11

9x9

7x7

5x5

3x3

1x1