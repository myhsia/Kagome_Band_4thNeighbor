Good afternoon, everyone. I'm Mingyu Xia. The topic of my pre. today is
`Band Structure of 2D Kagome Lattice`.

Firstly, I shall briefly introduce it.

So, what is Kagome? On geometry, it is a trihexagonal.
Sometimes, one can find that the floor in a certain area is spliced from it.
It first appeared in a paper by a Japanese physicist's assistant.
Concerning the group theory, it satisfies the `p6m` symmetry.
One can rotate it by $60^\circ$, then it remains unchanged; or mirror it by three axes.

Recently, people have devoted themselves to discovering new Kagome materials, studying their quantum spin liquid,
superconducting behaviors and topological properties.

Now, let's learn about its lattice structure.
U may be familiar with graphene, and in graphene, there are two kinds of sites.
However, in Kagome, there are three kinds of sites, labeled as $A$ (the blue ones),
$B$ (the red ones), and $C$ (the green ones) in the left figure.
The right figure illustrates the nearest-neighbor hopping within a single unit cell.

So, to calculate its band structure,
we can write the Hamiltonian by the tight-binding model in second quantization first.
Here, we only consider the nearest neighbor hopping.

But the operators in the Hamiltonian have different subscript labels.
To uniform it, we can take a Fourier transformation,
then, some terms will raise an extra phase factor
like $\mathrm e^{\mathrm i\bm k\cdot\bm\delta_i}$.

By substituting the transformed operators into the Hamiltonian, we can diagonalize
the Hamiltonian.

And one can obtain the eigen equation from the
determinant $\tilde{\mathcal H} - E\mathbb I = 0$.
For this case, it is a cubic equation, which will certainly cause three energy bands,
including two dispersive bands and one flat band.
Now, based on this equation, we can take some numerical calculations.

For simplicity, we take $t_1 = t_2 = t_3 = t$.
Then, the energy bands can be expressed like this,
and I used **Python** to plot the energy bands.

The first two figures show the 3D band structure; they just differ in perspective.
The third and fourth figures show the 2D band structure of the two dispersive bands in the $k_x$-$k_y$ plane, respectively, with the darker color standing for the higher energy.

We can also learn the properties around the Dirac point.
Just taking this vector in the momentum space.
Then, we can find that the dispersive band with a plus sign is equal to that of the flat band,
which can be implied in this figure: There are four tangent points.

If we take a small perturbation to the wave vector,
then we can find that the two dispersive bands are parabolic near the Dirac point.
This is a very common result.

Finally, beyond the NN hopping, we can also consider the NNN hopping even the NNNN hopping.
Then, the total Hamiltonian will have an extra term.
For example, the NNN hopping can be marked in this figure:
The hopping between $A$ and $B'$, between $B$ and $C'$, between $C$ and $A'$.

The extra Hamiltonian can be diagonalized like this,
and, interestingly, the NNNN Hamiltonian is diagonal.
It's straightforward, since in the NNNN hopping,
it can be a sum of $A$ and $A'$, $B$ and $B'$, $C$ and $C'$: the same labels.

OK. So much for today's pre. This is the reference for my project.

Thanks for listening. Any questions?