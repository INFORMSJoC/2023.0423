# Data for replication

There are two categories of networks used in our experiments: HT (human trafficking) networks and layered networks. Layered networks are subdivided into two groups according to the location of the special arcs in the network: Type 1 and Type 2.

# HT Networks
These are synthetic but realistic domestic sex trafficking network generated according to the method from ``Kosmas et al. (2023), _A transdisciplinary approach for generating synthetic but realistic domestic sex trafficking networks_. IISE Transactions 56(3):1–15.'' In these network, the first row contains only two entries: the first indicates the source node and the second entry indicates the sink node. All the remaining rows denote arcs and their attributes, and have the following fields (in the following order):

``tail node, head node, arc capacity, arc interdiction cost, _Special_ indicator (indicates whether the arc is a special arc (1) or not (0)), _Trafficker_ indicator (indicates whether the arc is a trafficker arc (1) or not (0)), _Bottom_ indicator (indicates whether the arc is a bottom arc (1) or not (0)), _Victim_ indicator (indicates whether the arc is a victim arc (1) or not (0)).''

# Layered networks
Layered networks are created according to the procedure discussed in Section 6.2 of the paper. The first row of layered networks contains three entries: souce node, sink node, level in which the special arcs are located (1 for Type1 networks, 2 for Type2 networks). All the remaining rows denote arcs and their attributes, and have the following fields (in the following order):

"tail node, head node, arc capacity, arc interdiction cost, _Special_ indicator (indicates whether the arc is a special arc (1) or not (0)), _Level_ indicator (indicates in which level the arc is located: 0, 1, 2, 3, 4).''

# Modified Networks
The MFNIP Method proposed in the paper uses a modified network as discussed in Section 4.3 of the paper. Althoug the conversion from the original network to the corresponding modified network is straightforward, we also provide the modified network corresponding to each of the networks used in our experiments for the sake of completeness.
