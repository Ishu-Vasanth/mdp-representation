# MDP REPRESENTATION

## AIM:
To represent any one real-world problem in Markov Decision Process (MDP).

## PROBLEM STATEMENT:

### Problem Description
Plants are important due to its various beneficial factors.With reinforcement learning we can train a agent to ensure the growth of a saplings.

### State Space
{Dead, Sapling, Plant} -> {0,1,2}

### Sample State
Sapling

### Action Space
{Pouring water on regular interval, not pouring water} -> {0,1}

### Sample Action
Pouring water on regular interval

### Reward Function
R={ +1 , on pouring water regularly
     0 , otherwise
  }

### Graphical Representation
![RE](https://github.com/Ishu-Vasanth/mdp-representation/assets/94154614/5cf3cf79-695c-45e6-ab84-bf336bd692a1)

## PYTHON REPRESENTATION:
Developed by: ISHWARYA V
Register No: 212221240016

```
P={0: {0: [(1.0, 0, 0.0, True)],
       1: [(1.0, 0, 0.0, True)]},
   1: {0: [(1.0, 0, 0.0, True)],
       1: [(1.0, 2, 1.0, True)]},
   2: {0: [(1.0, 2, 0.0, True)],
       1: [(1.0, 2, 0.0, True)]}
  }
```

## OUTPUT:
![op](https://github.com/Ishu-Vasanth/mdp-representation/assets/94154614/285c8705-a3da-46bc-a3cb-34fa6383147a)

## RESULT:
Thus, a real-world problem is represented in MDP form.
