Sort array by objects' attribute
===

    a = [answer1, answer2, answer3]
    a.sort { |a, b| a.votes_point <=> b.votes_point } # swap a & b to reverse the sort
