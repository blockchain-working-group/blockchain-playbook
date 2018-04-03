---
title: Appendix A
layout: page
permalink: /appendices/A/
---

# Appendix A – Blockchain Types & Best Fit

## Blockchain Types [6]
The following tables describe different types of blockchain

<table>
    <thead>
        <tr>
            <th scope="col" colspan="2">Public/Permissionless Blockchain<br/>Any participant is able to become a validator for transactions</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th scope="row">Features</th>
            <td>
                <ul>
             <li>Public blockchain supports multiple readers and writers with open read/write. There is no need to be part of a group or consortium to participate in the network.</li>
             <li>High public verifiability.</li>
             <li>Consistent state of blockchain across all users.</li>
             <li>Potential to disrupt current business models through disintermediation. No middle man or intermediary required as the ledger of transactions and set of programs to update the ledger is shared across every node in blockchain.</li>
             <li>Unrestricted and open membership with access to data. Anyone can join the network, access the transactions, and participate in consensus.</li>
             <li>Slower compared to other types because a large number of designated nodes are involved in validating transaction blocks.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <th scope="row">Context</th>
            <td>
                <ul>
             <li>Open source and permissionless so anyone can download the code and validate the transactions (validating integrity of blocks by participating in consensus).</li>
             <li>Anyone in the world can send transactions through the network and expect to see them included in the blockchain if they are valid.</li>
             <li>Anyone can read transactions on the public block explorer and transactions are transparent, but pseudonymous (an encrypted unique 64-character key).</li>
             <li>Public blockchains hold the potential to replace most functions of traditional financial institutions with software fundamentally reshaping the way the financial system works.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th scope="col" colspan="2">Public Consortium Blockchain<br/>Pre-selected parties are able to validate transactions</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th scope="row">Features</th>
            <td>
                <ul>
                    <li>High throughput and scalability as a relative number of validators is low compared to public blockchain.</li>
                    <li>Federated or consortium blockchains operate under the governance of a group (government agencies or financial institutions) which decide the criteria for others to participate in the blockchain network.</li>
                    <li>High transaction privacy as any write and consensus access to the blockchain is controlled based on permissions configured by consortium peer nodes.</li>
                    <li>The consensus process is controlled by a set of nodes meeting certain pre-defined consensus criteria. For example, a consortium of 15 financial institutions, each of which operates a node and 10 nodes must sign every block in order for the block to be valid and added to the blockchain.</li>
                    <li>Tailorable consensus algorithms with flexible chain trust model. For example, a chain may contain 15 nodes, but only 10 may be required to provide consensus to write to the chain.</li>
                    <li>Membership with identity-based access (including read/write controls) on data. The identity is decided and controlled by the governing body.</li>
                    <li>Faster and permissioned read/writes.</li>
                    <li>Anyone who meets certain pre-defined criteria can download the code and participate in validating the transactions.</li>
                </ul>
             </td>
        </tr>
        <tr>
            <th scope="row">Context</th>
            <td>
                <ul>
                    <li>Consortium of government and financial institutions would have one or more peer nodes and each node would have a copy of the ledger and participate in validating the transactions. Other institutions or the general public could be granted limited access, e.g. read-only.</li>
                    <li>Potential applications across both financial and non-financial use cases in government or multi- organization blockchain networks allowing controlled access based on individual needs.</li>
                </ul>
             </td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th scope="col" colspan="2">Private Consortium Blockchain<br/>A single group controls validating transactions</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th scope="row">Features</th>
            <td>
                <ul>
                    <li>Higher throughput due to lower number of validators (compared to permissionless blockchains).</li>
                    <li>Federated or consortium blockchains operate under the governance of a group (e.g. government agencies or financial institutions) which decide the criteria for other clients to participate.</li>
                    <li>High transaction privacy as any access to the blockchain is controlled based on permissions configured by the consortium control node(s).</li>
                    <li>The consensus process is controlled by the control group node(s) who also determine who will participate in endorsement and ordering of the transaction blocks. This allows for custom-defined consensus algorithms but client nodes cannot participate in consensus.</li>
                    <li>Membership with identity-based access (including read/write controls) on data. For example, a chain may contain 15 nodes, but only 10 may be required to provide consensus to write to the chain.</li>
                    <li>Consortium peer nodes have the blockchain ledger and state database with client-only access to blockchain network based on access permissions. Clients will not have access to ledger.</li>
                    <li>Faster and permissioned read/writes with only pre-selected nodes determined by administrator nodes in consortium participate in consensus.</li>
                </ul>
             </td>
        </tr>
        <tr>
            <th scope="row">Context</th>
            <td>
                <ul>
                    <li>Consortium of government and financial institutions would have one or more peer nodes and each node would have a copy of the ledger but only control or administrator nodes could participate in consensus. Select participants could be granted limited access, e.g. read-only.</li>
                    <li>Potential applications across both financial and non-financial use cases in government or multi- organization blockchain networks allowing controlled access in a private system.</li>
                </ul>
             </td>
        </tr>
    </tbody>
</table>

## Which Type of Blockchain Is the Best Fit for My Organization?
The following two tables explore different aspects of blockchain to help figure out which blockchain type is the best fit. The tables have been broken down in two pieces for better readability.

<table>
    <thead>
        <tr>
            <th scope="col"></th>
            <th scope="col">Need to Store State (Ledger + state)?</th>
            <th scope="col">Multiple writers</th>
            <th scope="col">Use online Third Trusted Party always?</th>
            <th scope="col">Always Trusted Writers</th>
            <th scope="col">Public Verifiability Required</th>
            <th scope="col">Settlement Finality (Irreversible)</th>
        </tr>
    </thead>
    <tbody>
        {% for bct in site.data.appendixA-data.blockchain-types %}
        <tr>
            <th scope="row">{{ bct.type }}</th>
            <td>{{ bct.col1 }}</td>
            <td>{{ bct.col2 }}</td>
            <td>{{ bct.col3 }}</td>
            <td>{{ bct.col4 }}</td>
            <td>{{ bct.col5 }}</td>
            <td>{{ bct.col6 }}</td>
        </tr>
        {% endfor %}
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th scope="col"></th>
            <th scope="col">Censorship</th>
            <th scope="col">Validators</th>
            <th scope="col">Assets Suitability</th>
            <th scope="col">Deployment</th>
        </tr>
    </thead>
    <tbody>
        {% for bct in site.data.appendixA-data.blockchain-types %}
        <tr>
            <th scope="row">{{ bct.type }}</th>
            <td>{{ bct.col7 }}</td>
            <td>{{ bct.col8 }}</td>
            <td>{{ bct.col9 }}</td>
            <td>{{ bct.col10 }}</td>
        </tr>
        {% endfor %}
    </tbody>
</table>