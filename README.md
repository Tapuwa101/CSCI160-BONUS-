# CSCI160-BONUS-

The Greedy approach finds the optimal position for each transmitter to cover the maximum number of houses. t finds the farthest house within the range of a transmitter and places a transmitter there, then skips the houses covered by this transmitter.
Time Complexity Measurement: The primary operation is iterating through the sorted list of houses. If n is the number of houses, the time complexity is O(nlogn).

Dynamic Programming:
we calculate the minimum cost of covering houses up to a certain point. This requires keeping track of the minimum cost for each house, considering the range of the transmitters and their costs.When each transmitter has a different cost, the state of the DP needs to incorporate the cost factor. For each house, we consider the cost of placing a transmitter at that house and the minimum cost of covering all previous houses.
Time Complexity: The time complexity of DP is often calculated based on the number of states times the complexity of computing each state. :O(n).
