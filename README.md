# Approval Voting for the UK

This repository contains the source code for a single-page site advocating for the adoption of approval voting in the United Kingdom.

## Goals of this Page

*   Clearly demonstrate the advantages of Approval Voting and Proportional Approval Voting for the UK, focusing on Labour, the current party in power.
*   Compare and contrast it with First Past the Post (FPTP) and Ranked Choice Voting (RCV)/Alternative Vote/Instant-Runoff Voting (IRV).
*   Separately demonstrate proportionality.
*   Discuss both single-winner elections, such as for directly elected mayors, and how proportionality would be implemented for parliamentary elections.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   Node.js
*   npm

### Installation

1.  Clone the repo
    ```sh
	git clone https://github.com/fsargent/approvalvoting.co.uk.git
    ```
2.  Install browser-sync
    ```sh
    npm install -g browser-sync
    ```
3.  Run the server
    ```sh
    browser-sync start --server --files "*.html, *.css"
    ```

The site will be available at `http://localhost:3000`.
