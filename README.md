# ewsn2018
Dataset generated during the experiments of the paper ' Passive Link Quality Estimation for Accurate and Stable Parent Selection in Dense 6TiSCH Networks' (EWSN 2018)(R. Teles Hermeto, A. Gallais, K. Van Laerhoven and F. Theoleyre)

1. broadcast_recepetion.csv and unicast_transmissions.csv
Datasets generated for the Pearson (Figure 6), Spearman (Figure 7), ranking efficiency (Figure 9), end-to-end (Figure 12) PDR and end-to-end delay (Figure 13). In Pearson, Spearman experiments the target node's id is '8561'.

Broadcast columns: node_id, sender, asn, time, channel, is_eb (1 = EB, 0 = DIO)
Unicast columns: node_id, destination, asn, time, ack, tx (tries), channel of the last attempt


2. broadcast_recepetion(10,13,16,19) and unicast_transmissions(10,13,16,19)
Datasets generated for the density experiment (Figure 10).

3. Parent changes (Figure 14).
