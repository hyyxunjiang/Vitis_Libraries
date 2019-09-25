
.. 
   Copyright 2019 Xilinx, Inc.
  
   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at
  
       http://www.apache.org/licenses/LICENSE-2.0
  
   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

*******************************************************
Singular Value Decomposition for general matrix (GESVJ)
*******************************************************

This function implements singular value decomposition of matrix A using one-sided Jacobi algorihtm.

.. math::
     A = U \Sigma V^T
 
where :math:`A` is a dense symmetric matrix of size :math:`rows \times cols`, :math:`U` is :math:`rows \times rows` matrix with orthonormal columnsand and :math:`V` is :math:`cols \times cols` matrix with orthonormal columns, and :math:`\Sigma` is diagonal matrix.
The maximum matrix size supported in FPGA is templated by MAXM, MAXN.