# Electronic Voting System

## Project Overview

The Electronic Voting System is a console-based Python application that allows a group of individuals to vote in a secure, anonymous, and tamper-proof manner. The system ensures that votes are cast fairly, votes cannot be tampered with, and the voting process is carried out with integrity.

### Key Features:
- **Anonymity**: Voter identities are kept anonymous using randomly generated voter IDs.
- **Integrity**: Votes are securely hashed using SHA-256 to prevent tampering.
- **Vote Validation**: Ensures that votes are cast for valid candidates only.
- **Duplicate Voting Prevention**: Each voter can only vote once.
- **Result Tallying**: The system tallies votes and announces the winner or declares a tie.

## Goals
- Ensure that users cannot see any information about other votes.
- Prevent any possibility of vote tampering or fraud.
- Provide a fair and just voting process.

## Installation

To run the Electronic Voting System, you'll need to have Python installed on your machine.

### Steps to Install:

1. **Clone the repository or download the code**:
   - Clone using Git:
     ```bash
     git clone <repository-url>
     ```
   - Or download the code directly as a ZIP file and extract it.

2. **Navigate to the project directory**:
   ```bash
   cd path/to/electronic-voting-system
