# Research Interests
 <dl>
 <dt>Advanced Finite Element Methods (FEMs)</dt>
  
   <dd> Unfitted FEMs</dd>

 <dt> Numerical Analysis of Fractional PDEs</dt>
  
 <dd> Standard and Nonstandard FEMs</dd>

 <dt>Techniques</dt> 

  <dd> Nitsche's Methods, CutFEMs</dd> 
  <dd> Eigenfunction Expansion, Operator Theoretic Approach, Energy Arguments, Convolution Quadratures, L1 scheme</dd> 

 <dt>Applications</dt> 
 
  <dd> Interface Problems, Dynamics of Anomalous Diffusion Processes</dd> 

</dl>



My research interests are in the field of numerical analysis, in particular, the finite element method. Here is an example: Let us consider the Laplace's equation

$$
\begin{eqnarray}
-\Delta u &=& f \quad \text{in  } \Omega \\
u &=& 0 \quad  \text{on  } \partial\Omega
\end{eqnarray}
$$

The weak formulation of the above BVP is given by: find \\(u \in H^1_0(\Omega)\\) such that

$$
\begin{equation}
  \int_\Omega \nabla u \cdot \nabla v \, dx = \int_\Omega f v \, dx 
\end{equation}
$$

for all \\(v \in H^1_0(\Omega)\\).
