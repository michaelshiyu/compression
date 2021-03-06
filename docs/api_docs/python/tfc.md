
# Module: tfc



Defined in [`__init__.py`](https://github.com/tensorflow/compression/tree/master/__init__.py).

<!-- Placeholder for "Used in" -->

Data compression tools.

## Modules

[`python`](./tfc/python.md) module

## Classes

[`class EntropyBottleneck`](./tfc/EntropyBottleneck.md): Entropy bottleneck layer.

[`class EntropyModel`](./tfc/EntropyModel.md): Entropy model (base class).

[`class GDN`](./tfc/GDN.md): Generalized divisive normalization layer.

[`class GaussianConditional`](./tfc/GaussianConditional.md): Conditional Gaussian entropy model.

[`class IdentityInitializer`](./tfc/IdentityInitializer.md): Initialize to the identity kernel with the given shape.

[`class LaplacianConditional`](./tfc/LaplacianConditional.md): Conditional Laplacian entropy model.

[`class LogisticConditional`](./tfc/LogisticConditional.md): Conditional logistic entropy model.

[`class NonnegativeParameterizer`](./tfc/NonnegativeParameterizer.md): Object encapsulating nonnegative parameterization as needed for GDN.

[`class Parameterizer`](./tfc/Parameterizer.md): Parameterization object (abstract base class).

[`class RDFTParameterizer`](./tfc/RDFTParameterizer.md): Object encapsulating RDFT reparameterization.

[`class SignalConv1D`](./tfc/SignalConv1D.md): 1D convolution layer.

[`class SignalConv2D`](./tfc/SignalConv2D.md): 2D convolution layer.

[`class SignalConv3D`](./tfc/SignalConv3D.md): 3D convolution layer.

[`class StaticParameterizer`](./tfc/StaticParameterizer.md): A parameterizer that always returns a constant tensor.

[`class SymmetricConditional`](./tfc/SymmetricConditional.md): Symmetric conditional entropy model.

## Functions

[`array_fingerprint(...)`](./tfc/array_fingerprint.md): Produces fingerprint of the input data.

[`check_array_fingerprint(...)`](./tfc/check_array_fingerprint.md): Computes the fingerprint of `input` and checks the computed value against

[`irdft_matrix(...)`](./tfc/irdft_matrix.md): Matrix for implementing kernel reparameterization with `tf.matmul`.

[`lower_bound(...)`](./tfc/lower_bound.md): Same as `tf.maximum`, but with helpful gradient for `inputs < bound`.

[`pmf_to_quantized_cdf(...)`](./tfc/pmf_to_quantized_cdf.md): Converts PMF to quantized CDF. This op uses floating-point operations

[`range_decode(...)`](./tfc/range_decode.md): Decodes a range-coded `code` into an int32 tensor of shape `shape`.

[`range_encode(...)`](./tfc/range_encode.md): Using the provided cumulative distribution functions (CDF) inside `cdf`, returns

[`same_padding_for_kernel(...)`](./tfc/same_padding_for_kernel.md): Determine correct amount of padding for `same` convolution.

[`unbounded_index_range_decode(...)`](./tfc/unbounded_index_range_decode.md): This is the reverse op of `UnboundedIndexRangeEncode`, and decodes the range

[`unbounded_index_range_encode(...)`](./tfc/unbounded_index_range_encode.md): Range encodes unbounded integer `data` using an indexed probability table.

[`upper_bound(...)`](./tfc/upper_bound.md): Same as `tf.minimum`, but with helpful gradient for `inputs > bound`.

