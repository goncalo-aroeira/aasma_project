# AAMS Beehive Simulation

This project implements a multiagent system to simulate bee colony foraging behavior, developed as part of the Autonomous Agents and Multiagent Systems (AASMA) course at Instituto Superior Técnico. The goal is to explore the interactions between bee colonies, food sources, and their environment, providing insights into collective foraging behaviors and survival strategies.

Using a decentralized approach, each bee agent makes decisions based on local information and simple rules, leading to emergent colony-wide behaviors. The simulation models real-world ecological challenges, such as food scarcity, competition, and predation, by incorporating different bee types, queen strategies, and predator threats (wasps).

Key Features:
1. Decentralized multiagent system with autonomous decision-making.
2. Foraging and resource management, with realistic food depletion and regrowth.
3. Colony survival dynamics, including birth rates, population control, and strategic hive management.
4. Multiple bee strategies, such as greedy, social, and respectful behaviors.
5. Predation and defense mechanics, introducing wasps as external threats.
6. Extensive experimentation and performance analysis, with different environmental setups.

Demo Video: https://youtu.be/QQ6ufTtMS0k 

## Installation

0. Make sure you have Python 3.11 or later installed.

1. Clone the repository:

```shell
git clone https://github.com/joao-hs/aams-beehive-simulation.git
```

2. Create a virtual environment:

```shell
python -m venv .venv
```

3. Activate the virtual environment:

```shell
source .venv/bin/activate
```

4. Install the required dependencies:

```shell
pip install -r requirements.txt
```

## Usage

To run the simulation, execute the following command:

```shell
python main.py <path/to/config/file.json>
```

You can create your own configuration file based on the `config/base.json` file, in order to explore different scenarios.
