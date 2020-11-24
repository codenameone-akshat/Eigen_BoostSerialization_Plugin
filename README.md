# Eigen_BoostSerialization_Plugin
Boost Serialization of Eigen Dense and Sparse Matrix.
This is just a fork of [mtao/eigen_boost_serialization gist] with loss of data warning fixed.

# Dependencies
Boost must be set in the include directories and the file includes the file like  
`#include <boost/serialization/vector.hpp>`

# Usage
Copy and Paste file into Eigen/ directory along with the other headers.

[mtao/eigen_boost_serialization gist]: https://gist.github.com/mtao/5798888
