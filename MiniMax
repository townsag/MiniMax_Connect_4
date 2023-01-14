import copy
import sys


def main():
    # test_game_board = [
    #     ['Y', 'E', 'E', 'E', 'E'],
    #     ['E', 'Y', 'E', 'E', 'E'],
    #     ['E', 'E', 'Y', 'E', 'E'],
    #     ['E', 'E', 'E', 'Y', 'E'],
    #     ['E', 'E', 'E', 'Y', 'E'],
    #     ['E', 'E', 'E', 'E', 'E'],
    #     ['E', 'E', 'E', 'E', 'E'],
    #     ['E', 'E', 'E', 'E', 'E']
    # ]
    #
    # draw_board(test_game_board)
    # print(check_game_state(test_game_board))
    #
    # print_input_move('Y', '1-a-n')
    # print_input_move('R', '1-a-n')
    #
    # print(f"checking flip: h-1-1: {is_valid_flip(test_game_board, 'h-1-1', True)}")
    # print("^should be False")
    # print(f"checking flip: h-1-2: {is_valid_flip(test_game_board, 'h-1-2', True)}")
    # print("^should be True")
    # print(f"checking flip: h-1-2: {is_valid_flip(test_game_board, 'h-1-4', True)}")
    # print("^should be False")

    # test_game_board2 = [
    #     ['Y', 'R', 'E'],
    #     ['R', 'Y', 'R'],
    #     ['E', 'E', 'Y']
    # ]
    # draw_board(test_game_board2)
    # valid_moves = get_actions(test_game_board2, True)
    # print(valid_moves)
    #
    # print('\n\n\nmaking move: c-1-n for Y')
    # update_board(test_game_board2, 'Y', 'c-1-n')
    # draw_board(test_game_board2)
    #
    # print('\n\n\nmaking move: a-3-2 for R')
    # update_board(test_game_board2, 'R', 'a-3-2')
    # draw_board(test_game_board2)
    #
    # print('output of the check game function (game over, red wins, yellow wins)')
    # print(check_game_state(test_game_board2))

    """
    test_game_board1 = [
        ['Y', 'R', 'R', 'R', 'R'],
        ['E', 'Y', 'E', 'E', 'R'],
        ['R', 'R', 'E', 'Y', 'E'],
        ['E', 'Y', 'E', 'Y', 'E'],
        ['Y', 'E', 'E', 'Y', 'E']
    ]

    test_game_board2 = [
        ['Y', 'E', 'R', 'R', 'R'],
        ['E', 'Y', 'E', 'E', 'R'],
        ['R', 'R', 'Y', 'Y', 'E'],
        ['E', 'Y', 'E', 'Y', 'E'],
        ['Y', 'E', 'E', 'Y', 'E']
    ]

    test_game_board3 = [
        ['Y', 'R', 'R', 'R', 'R'],
        ['E', 'Y', 'E', 'E', 'R'],
        ['R', 'R', 'Y', 'Y', 'E'],
        ['E', 'Y', 'E', 'Y', 'E'],
        ['Y', 'E', 'E', 'Y', 'E']
    ]

    test_game_board4 = [
        ['Y', 'Y', 'R', 'R', 'Y'],
        ['R', 'R', 'Y', 'Y', 'R'],
        ['Y', 'Y', 'R', 'R', 'Y'],
        ['R', 'R', 'Y', 'Y', 'R'],
        ['Y', 'Y', 'R', 'R', 'Y']
    ]

    test_game_board5 = [
        ['Y', 'R', 'E', 'R', 'R'],
        ['E', 'Y', 'E', 'E', 'R'],
        ['R', 'R', 'E', 'Y', 'E'],
        ['E', 'Y', 'E', 'Y', 'E'],
        ['Y', 'E', 'E', 'Y', 'E']
    ]


    print('output of the check game function (game over, red wins, yellow wins)')
    draw_board(test_game_board1)
    print('for gameboard one (red wins): ', end='')
    print(check_game_state(test_game_board1), end='\n\n')

    draw_board(test_game_board2)
    print('for gameboard two (yellow wins): ', end='')
    print(check_game_state(test_game_board2), end='\n\n')

    draw_board(test_game_board3)
    print('for gameboard two (both win): ', end='')
    print(check_game_state(test_game_board3), end='\n\n')

    draw_board(test_game_board4)
    print('for gameboard two (draw, full board): ', end='')
    print(check_game_state(test_game_board4), end='\n\n')

    draw_board(test_game_board5)
    print('for gameboard two (in progress): ', end='')
    print(check_game_state(test_game_board5), end='\n\n')"""

    # test_game_board1 = [
    #     ['Y', 'R', 'E'],
    #     ['R', 'Y', 'R'],
    #     ['E', 'E', 'Y']
    # ]
    # draw_board(test_game_board1)
    # print('\n\ntesting number of in a rows yellow, 2: ' + str(count_in_a_rows(test_game_board1, True, 2)))
    # print('testing number of in a rows red, 2: ' + str(count_in_a_rows(test_game_board1, False, 2)))
    # print('testing number of in a rows yellow, 3: ' + str(count_in_a_rows(test_game_board1, True, 3)))
    # print('testing number of in a rows red, 3: ' + str(count_in_a_rows(test_game_board1, False, 3)))
    """
    16, b - 4 - n, 9223372036854775807
    17, b - 4 - 1, 9223372036854775807
    18, b - 4 - 2, 9223372036854775807
    19, b - 4 - 3, 9223372036854775807
    20, b - 4 - 4, 9223372036854775807
    21, b - 4 - 5, 9223372036854775807
    22, c - 2 - n, 9223372036854775807
    23, c - 2 - 1, 9223372036854775807
    24, c - 2 - 3, 9223372036854775807
    25, c - 2 - 5, 9223372036854775807
    26, c - 3 - n, 9223372036854775807
    27, c - 3 - 1, 9223372036854775807
    28, c - 3 - 2, 9223372036854775807
    29, c - 3 - 3, 9223372036854775807
    30, c - 3 - 5, 9223372036854775807
    31, c - 4 - n, 9223372036854775807
    32, c - 4 - 1, 9223372036854775807
    33, c - 4 - 2, 9223372036854775807
    34, c - 4 - 3, 9223372036854775807
    35, c - 4 - 4, 9223372036854775807
    36, c - 4 - 5, 9223372036854775807
    37, c - 5 - n, 7
    38, c - 5 - 1, 7
    39, c - 5 - 2, 7
    40, c - 5 - 3, 7
    41, c - 5 - 5, 7
    """

    """
    test_game_board = [
        ['R', 'E', 'Y', 'E', 'E'],
        ['Y', 'Y', 'Y', 'E', 'R'],
        ['R', 'E', 'E', 'E', 'E'],
        ['R', 'E', 'E', 'E', 'R'],
    ]

    print("board before the move: ")
    draw_board(test_game_board)

    print("\n\n performing the move: b-4-n for player Y")
    test_game_board_copy1 = copy.deepcopy(test_game_board)
    update_board(test_game_board_copy1, 'Y', 'b-4-n')
    draw_board(test_game_board_copy1)

    print('\n\nresults of move (terminal, red wins, yellow wins:')
    print(check_game_state(test_game_board_copy1))

    print("\n\nboard before the move: ")
    draw_board(test_game_board)

    print("\n\n performing the move: b-4-1 for player Y")
    test_game_board_copy2 = copy.deepcopy(test_game_board)
    update_board(test_game_board_copy2, 'Y', 'b-4-1')
    draw_board(test_game_board_copy2)

    print('\n\nresults of move (terminal, red wins, yellow wins:')
    print(check_game_state(test_game_board_copy2))
    """

    player_color_choice: str = get_player_color()
    play_connect_4(player_color_choice)


def play_connect_4(player_color_choice: str):
    game_board: list[list[str, ...], ...] = [["E"] * 5 for i in range(8)]
    # game_board: list[list[str, ...], ...] = [["E"] * 5 for i in range(3)]
    # the player whose turn it is currently is stored as a boolean value
    # True means yellows turn and False means reds turn
    # after each turn we switch over to the opposite boolean value
    color_dict: dict[str, bool] = {'Y': True, 'R': False}
    player_dict: dict[bool, str] = {True: 'Y', False: 'R'}
    # the human player goes first
    current_move_player: bool = color_dict[player_color_choice]
    game_over: bool = False
    red_wins: bool = False
    yellow_wins: bool = False

    while not game_over:
        draw_board(game_board)
        print(f'current player: {player_dict[current_move_player]}')
        # check to see if the current player is a PC or NPC
        move = None
        if current_move_player == color_dict[player_color_choice]:  # the current player is the human player
            move = get_player_move(game_board)

        else:  # this means that the current play is the computer player
            # move = mini_max_decision(game_board, current_move_player, 3)
            move = mini_max_decision(game_board, current_move_player, 4)

        update_board(game_board, player_dict[current_move_player], move)
        print_input_move(player_dict[current_move_player], move)
        current_move_player = not current_move_player
        game_over, red_wins, yellow_wins = check_game_state(game_board)

    draw_board(game_board)

    # now that the game is over, display the result of the game winner(s) tie or draw


# inputs: game_board-2D array, player-string in ['Y','R'], row-int
#         move is a string of the format r-c-f or row (as a string a-h) column (as a number 1-5) and either n or a col
def update_board(game_board: list[list[str, ...], ...], player: str, move: str):
    row_index_dict = {'a': 0, 'b': 1, 'c': 2, 'd': 3, 'e': 4, 'f': 5, 'g': 6, 'h': 7}
    row = row_index_dict[move[0]]
    column = int(move[2]) - 1
    # insert the token on the board
    game_board[row][column] = player
    # flip the column
    # create a temporary column that we can then flip
    temp_column = []
    if move[4] != 'n':
        for i in range(len(game_board)):
            temp_column.append(game_board[i][int(move[4]) - 1])
        for i in range(len(game_board)):
            game_board[i][int(move[4]) - 1] = temp_column.pop()  # pop returns the last element in the array


# this function takes a game board as an input then says whether a player has won
# bool: game over, bool: red wins, bool: yellow wins
# five possible states:
#   - red wins                                                              true, true, false
#   - yellow wins
#   - tie (both players win simultaneously, the result of a flipped board
#   - draw, all the spaces are full and nobody wins
#   - not terminal, the game is still going and nobody has won
def check_game_state(game_board: list[list[str, ...], ...]) -> (bool, bool, bool):
    # try brute force first (altrnatively try dfs
    board_height = len(game_board)
    board_width = len(game_board[0])
    red_num_wins = 0
    yellow_num_wins = 0
    full_board = True
    directions: list = [(1, 0), (0, 1), (1, -1), (1, 1)]

    for i in range(board_height):  # iteratively checks down the board
        for j in range(board_width):  # iteratively checks from left to right
            # check if this piece is ocupied
            if game_board[i][j] == "E":
                full_board = full_board and False
            else:
                # check if any 4 in a rows start at this piece: vertical and down, horizontal to the right, diagonal down
                # and to the left, diagonal down and to the right
                for direction in directions:
                    # check to see if all four locations in this direction are filled with the same players piece
                    temp_locations = list()
                    # for k in range(4):
                    #     temp_locations.append((i + k * direction[0], j + k * direction[1]))
                    loc0 = (i, j)
                    loc1 = (i + direction[0], j + direction[1])
                    loc2 = (i + 2 * direction[0], j + 2 * direction[1])
                    loc3 = (i + 3 * direction[0], j + 3 * direction[1])
                    # make sure that the end of the potential 4 in-a-row is not outside the game-board
                    if 0 <= loc3[0] < board_height and 0 <= loc3[1] < board_width:
                        # check that all the locations have the same symbol
                        if check_positions(game_board, loc0, loc1, loc2, loc3, "R"):
                            red_num_wins += 1
                        elif check_positions(game_board, loc0, loc1, loc2, loc3, "Y"):
                            yellow_num_wins += 1
    if red_num_wins != 0 and yellow_num_wins == 0:
        return True, True, False
    elif red_num_wins == 0 and yellow_num_wins != 0:
        return True, False, True
    elif red_num_wins != 0 and yellow_num_wins != 0:
        return True, True, True
    elif full_board:
        return True, False, False
    else:
        return False, False, False


# returns true if all 4 positions on the game board contain the target string (either 'Y' or 'R')
def check_positions(game_board: list[list[str, ...], ...], loc0: tuple[int, int], loc1: tuple[int, int],
                    loc2: tuple[int, int], loc3: tuple[int, int], target: str) -> bool:
    if game_board[loc0[0]][loc0[1]] == game_board[loc1[0]][loc1[1]] == game_board[loc2[0]][loc2[1]] == \
            game_board[loc3[0]][loc3[1]] == target:
        return True


def draw_board(game_board: list[list[str, ...], ...]):
    color = {"R": "\033[91m", "Y": "\033[93m", "E": "\033[0m"}
    row_letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h']
    print("  1 2 3 4 5\n +-+-+-+-+-+")

    for i in range(len(game_board)):
        print(f'{row_letters[i]}|', end='')
        for j in range(len(game_board[i])):
            print(color[game_board[i][j]] + game_board[i][j] + "\033[0m|", end='')
        print("\n +-+-+-+-+-+")


def get_player_color():
    whitelist = ['Y', 'R']
    choice = input('Which player would you like to play (R/Y)? ')

    while choice not in whitelist:
        print('\nplease enter a single character from the options \'R\' or \'Y\' followed by enter')
        choice = input('Which player would you like to play (R/Y)? ')

    # return True if choice == 'Y' else False
    return choice


def get_player_move(game_board: list[list[str, ...], ...]) -> str:
    # row_index_dict = {'a': 0, 'b': 1, 'c': 2, 'd': 3, 'e': 4, 'f': 5, 'g': 6, 'h': 7}
    choice = input('Please enter your move (format row-column-flip_column): ')

    while (not check_move_format(choice)) or check_is_occupied(choice, game_board) or not check_input_in_range(choice):
        if not check_move_format(choice):
            print('please enter a string following the format ex: \'e-4-3\'')
            choice = input('Please enter your move (format row-column-flip_column): ')
        elif check_is_occupied(choice, game_board):
            print('that spot on the board is already occupied')
            choice = input('Please enter your move (format row-column-flip_column): ')
        elif not check_input_in_range(choice):
            print('one of your inputs is out of range')
            choice = input('Please enter your move (format row-column-flip_column): ')

    '''if (choice[4] == 'n'):
        return row_index_dict[choice[0]], int(choice[2]) - 1, False, 0
    else:
        return row_index_dict[choice[0]], int(choice[2]) - 1, True, int(choice[4]) - 1
    '''
    return choice


def check_move_format(choice: str) -> bool:
    row_whitelist = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h']
    column_whitelist = ['1', '2', '3', '4', '5']
    flip_column_whitelist = ['n', '1', '2', '3', '4', '5']
    return (len(choice) == 5) and (choice[0] in row_whitelist) and (choice[2] in column_whitelist) and \
        (choice[4] in flip_column_whitelist) and (choice[1] == choice[3] == '-')


def check_input_in_range(choice: str) -> bool:
    row_whitelist = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h']
    column_whitelist = ['1', '2', '3', '4', '5']
    flip_column_whitelist = ['n', '1', '2', '3', '4', '5']
    return (choice[0] in row_whitelist) or (choice[2] in column_whitelist) or (choice[4] in flip_column_whitelist)


def check_is_occupied(choice: str, game_board: list[list[str, ...], ...]):
    row_index_dict = {'a': 0, 'b': 1, 'c': 2, 'd': 3, 'e': 4, 'f': 5, 'g': 6, 'h': 7}
    temp_row = row_index_dict[choice[0]]
    temp_column = int(choice[2]) - 1
    return not (game_board[temp_row][temp_column] == 'E')


def print_input_move(current_player: str, move: str):
    if current_player == 'R':
        print('\033[91m' + 'player: ' + current_player + ' chose the move: ' + move + "\033[0m")
    elif current_player == 'Y':
        print('\033[93m' + 'player: ' + current_player + ' chose the move: ' + move + "\033[0m")


def mini_max_decision(game_board: list[list[str, ...], ...], current_move_player: bool, depth: int) -> str:
    # get all possible actions that the computer can take given the current state of the board
    potential_actions = get_actions(game_board, current_move_player)  # actions available to max
    best_value = -sys.maxsize
    best_action = potential_actions[0]

    alpha = -sys.maxsize
    beta = sys.maxsize

    count = 0
    total_calls = 0
    for action in potential_actions:
        # temp_value = minimum_value(game_board, not current_move_player, action)
        # print(depth)
        temp_value, num_function_calls = minimum_value(game_board, current_move_player, action, depth - 1, alpha, beta)
        num_function_calls += 1
        total_calls += num_function_calls
        print(str(count) + ", " + str(num_function_calls) + ', ' + action + ", " + str(temp_value))
        count += 1
        # current move player holds the identity of the current player at the time that the decision function was called
        if temp_value > best_value:
            best_value = temp_value
            alpha = temp_value
            best_action = action
    print('total calls: ' + str(total_calls))

    return best_action


def maximum_value(game_board: list[list[str]], max_player: bool, move: str, depth: int, alpha: int, beta: int) -> tuple[int, int]:
    player_dict: dict[bool, str] = {True: 'Y', False: 'R'}
    game_board_copy = copy.deepcopy(game_board)
    # update the copy board to reflect the move which is being evaluated
    update_board(game_board_copy, player_dict[not max_player], move)  # min just made this move

    # assumes that it is maxs turn, therefore max is current move player
    # right now we are evaluating the value of a move for max
    # assign maximum value to cases in which the current player wins
    terminal, red_wins, yellow_wins = check_game_state(game_board_copy)
    if terminal:  # checks for a terminal state (game is over)
        if (red_wins and yellow_wins) or (not red_wins and not yellow_wins):  # tie or draw
            return 0, 0
        elif max_player is True and yellow_wins:  # max player wins
            return sys.maxsize, 0
        elif max_player is False and red_wins:  # max player wins
            return sys.maxsize, 0
        else:  # max player loses
            return -sys.maxsize, 0

    if depth == 0:
        # use hueristic to evaluate this state for max
        return evaluate(game_board_copy, max_player), 0

    value = -sys.maxsize
    potential_actions = get_actions(game_board_copy, max_player)

    recursive_call_counter = 0
    for action in potential_actions:
        # print(depth)

        if beta <= alpha:
            break

        temp_min, temp_num_calls = minimum_value(game_board_copy, max_player, action, depth - 1, alpha, beta)

        if temp_min > alpha:
            alpha = temp_min

        value = max(value, temp_min)
        recursive_call_counter += 1 + temp_num_calls

    return value, recursive_call_counter


# return the minimum value of a boardstate given an action as well as the numbwe of recursive function calls generated
# by this function
def minimum_value(game_board: list[list[str]], max_player: bool, move: str, depth: int, alpha: int, beta: int) -> tuple[int, int]:
    player_dict: dict[bool, str] = {True: 'Y', False: 'R'}
    game_board_copy = copy.deepcopy(game_board)
    # update the copy board to reflect the move which is being evaluated
    update_board(game_board_copy, player_dict[max_player], move)  # the move was just performed by max, not min

    # assume that it is mins turn, therefore max is NOT the current move player
    # right now we are evaluating the value of a move for min
    # assign maximum value to cases in which the current player looses
    terminal, red_wins, yellow_wins = check_game_state(game_board_copy)
    if terminal:  # checks for a terminal state (game is over)
        if (red_wins and yellow_wins) or (not red_wins and not yellow_wins):  # tie or draw
            return 0, 0
        elif max_player is True and yellow_wins:  # max player wins
            return sys.maxsize, 0
        elif max_player is False and red_wins:  # max player wins
            return sys.maxsize, 0
        else:  # min player wins/ max player looses
            return -sys.maxsize, 0

    if depth == 0:
        # use hueristic to evaluate this state for max
        return evaluate(game_board_copy, max_player), 0

    value = sys.maxsize  # this is like the best to beat, minimum will choose the action with the lowest utility score
    potential_actions = get_actions(game_board_copy, not max_player)  # actions available to min

    recursive_call_counter = 0
    for action in potential_actions:
        # print(depth)

        if beta <= alpha:
            break

        temp_max, temp_num_calls = maximum_value(game_board_copy, max_player, action, depth - 1, alpha, beta)
        if beta > temp_max:
            beta = temp_max
        value = min(value, temp_max)
        recursive_call_counter += 1 + temp_num_calls

    return value, recursive_call_counter


def get_actions(game_board: list[list[str, ...], ...], current_move_player: bool) -> list[str, ...]:
    row_labels: list[str, ...] = ["a", "b", "c", "d", "e", "f", "g", "h"]
    board_height = len(game_board)
    board_width = len(game_board[0])
    valid_moves: list[str, ...] = list()
    # find the spaces on the board that are unoccupied
    for i in range(board_height):
        for j in range(board_width):
            if game_board[i][j] == 'E':
                potential_move = row_labels[i] + "-" + str(j + 1) + "-n"
                valid_moves.append(potential_move)

                # check to see if flipping each row from that point would produce a change
                for j2 in range(board_width):
                    potential_flip = row_labels[i] + "-" + str(j + 1) + "-" + str((j2 + 1))
                    if is_valid_flip(game_board, potential_flip, current_move_player):
                        valid_moves.append(potential_flip)
    return valid_moves


def is_valid_flip(game_board: list[list[str, ...], ...], potential_flip: str, current_move_player: bool) -> bool:
    row_index_dict = {'a': 0, 'b': 1, 'c': 2, 'd': 3, 'e': 4, 'f': 5, 'g': 6, 'h': 7}
    player_dict: dict[bool, str] = {True: 'Y', False: 'R'}
    row: int = row_index_dict[potential_flip[0]]
    move_column: int = int(potential_flip[2]) - 1
    flip_column: int = int(potential_flip[4]) - 1

    # create a copy of the row that is to be flipped
    temp_column = list()
    for i in range(len(game_board)):
        temp_column.append(game_board[i][flip_column])

    # if the potential move would change a piece in the column to be flipped, change that piece in the temp row
    if move_column == flip_column:
        temp_column[row] = player_dict[current_move_player]

    # check to see if a flipped version of the copied row is different from the normal version
    for i in range(len(temp_column) // 2):
        if temp_column[i] != temp_column[len(temp_column) - i - 1]:
            return True
    return False


def evaluate(game_board: list[list[str]], max_player: bool):
    # count the number of 3s and the number of 2s that max has and then
    num_3s_max = count_in_a_rows(game_board, max_player, 3)
    num_2s_max = count_in_a_rows(game_board, max_player, 2)
    num_3s_min = count_in_a_rows(game_board, not max_player, 3)
    num_2s_min = count_in_a_rows(game_board, not max_player, 2)
    # subtract from that the number of 3s and 2s that min has
    return (3 * num_3s_max) + num_2s_max - (3 * num_3s_min) - num_2s_min


# run length must be greater than one
def count_in_a_rows(game_board: list[list[str]], current_player: bool, run_length: int):
    player_dict: dict[bool, str] = {True: 'Y', False: 'R'}
    directions: list = [(1, 0), (0, 1), (1, -1), (1, 1)]
    num_in_a_rows = 0
    for i in range(len(game_board)):
        for j in range(len(game_board[i])):
            if game_board[i][j] != 'E':
                for direction in directions:
                    potential_run = list()
                    for k in range(run_length):
                        potential_run.append((i + direction[0] * k, j + direction[1] * k))

                    # check that the end of the run is in the bounds of the list
                    if 0 <= potential_run[-1][0] < len(game_board) and 0 <= potential_run[-1][1] < len(
                            game_board[potential_run[-1][0]]):
                        # check if all the pieces at the locations in the list are the same
                        same_flag = True
                        for k in range(run_length):
                            if game_board[potential_run[k][0]][potential_run[k][1]] == player_dict[current_player]:
                                same_flag = same_flag and True
                            else:
                                same_flag = same_flag and False

                        if same_flag:
                            num_in_a_rows += 1
    return num_in_a_rows


if __name__ == '__main__':
    main()
