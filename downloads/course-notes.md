# Finish the Game

Practical endgames with exact-result practice

Live course: https://knightway8.github.io/chess14/

## 01. The king becomes a working piece

**Goal:** Activate the king when tactical danger permits.

With fewer pieces, the king can attack pawns, escort passers, and control entry squares. Centralization is often useful, but not while enemy checks or mating threats make it unsafe. Count the squares the king can actually reach. A central king cut off by a rook may be less useful than a king with a clear route to the relevant wing.

### Worked explanation

In a pawn ending, a king may need to move toward a promotion square rather than toward the board’s geometric center. The objective determines the route.

### Try it yourself

For a simple ending, name the king’s most useful destination and count the minimum safe king moves needed to reach it.

### Answer

King distance uses the larger of file and rank differences on an empty board, because diagonal steps change both coordinates. Enemy control can make the actual route longer.

**Common mistake:** Moving the king toward the center automatically while a passed pawn races on the edge.

**Recall:** What determines king activity? Access to the squares that matter, subject to legal safety.

## 02. Checkmate and stalemate at the finish

**Goal:** Protect a win from accidental stalemate.

When the opponent has very little material, count their legal moves before making a quiet move. If their king is not in check and they have no legal move, the game is drawn by stalemate. A trapped king with a movable pawn is not stalemated. Checkmate requires check plus the absence of every legal response, including captures and blocks.

### Worked explanation

White king f7, queen g6, Black king h8, Black to move is stalemate. The queen covers g8 and h7, while the White king covers g7; h8 itself is not checked.

### Try it yourself

Set up that position, identify why each escape fails, then move the queen to a square that leaves a legal Black move.

### Answer

You should be able to name the preserved escape. Do not rely on a vague impression that the king has “some room.”

**Common mistake:** Assuming overwhelming material prevents a draw.

**Recall:** What should you check before a quiet move against a lone king? Whether the opponent will retain at least one legal move.

## 03. Queen and king: make the box smaller

**Goal:** Win with coordinated restriction instead of random checks.

Use the queen to restrict the enemy king to a smaller region, then bring your king closer. Keep the queen protected from capture and avoid reducing the opponent’s legal moves to zero without check. Once the king is on an edge, coordinate your king and queen to deliver mate. Checks are useful when they improve the restriction or finish the game, not merely because they are available.

### Worked explanation

A queen a knight’s move away from the enemy king often restricts it safely, but that geometric shortcut still needs a stalemate check. When the king reaches a corner, stop and inspect its legal moves before tightening further.

### Try it yourself

Play queen and king against king from a central position. After each move, describe the boundary of the enemy king’s box.

### Answer

The box should shrink or your king should improve. If repeated checks let the king return toward the center, revise the method.

**Common mistake:** Chasing with checks while your own king never joins the attack.

**Recall:** What are the two main tasks? Restrict the enemy king and bring your king close enough to support mate.

## 04. Rook and king: cut, approach, restrict

**Goal:** Use the rook’s barrier and the king’s support.

A rook can cut the enemy king off along a rank or file. Your king then approaches to help reduce the available space. Keep the rook far enough away to avoid capture and use waiting moves when the enemy king must yield ground. Mating positions commonly use a rook check on the edge with your king controlling the escape rank.

### Worked explanation

If your king is not close enough, a rook check may simply drive the enemy king sideways without progress. Improving the king while preserving the rook barrier can be the more useful move.

### Try it yourself

Play rook and king against king. Before checking, name which escape squares your king will cover after the check.

### Answer

If the answer is none, consider king improvement or a waiting rook move. Verify that the rook itself cannot be attacked and captured.

**Common mistake:** Putting the rook next to the enemy king without protection.

**Recall:** Why does the attacking king matter? It removes escape squares that the rook cannot cover alone.

## 05. Which material can force mate?

**Goal:** Separate possible mate from a forced win.

King and queen or king and rook can force mate against a lone king with correct play. Two bishops can also force mate; bishop and knight can, but the technique is demanding. King and a single bishop or knight cannot mate a lone king. Two knights cannot force mate against a lone king under ordinary best defense, although mating positions can exist with cooperation.

### Worked explanation

An extra bishop in king-and-bishop versus king is not a winning material advantage. The game is a dead position because no legal sequence can lead to checkmate.

### Try it yourself

Classify queen, rook, bishop, knight, two bishops, bishop-plus-knight, and two knights against a lone king.

### Answer

Distinguish “mate impossible,” “mate possible but not forced,” and “mate can be forced.” Those are different claims.

**Common mistake:** Assuming any extra piece must eventually win.

**Recall:** Can two knights force mate against a lone king? No, although a mating position can occur if the defender cooperates.

## 06. Draw rules and the position’s history

**Goal:** Know what a diagram can and cannot tell you.

A dead position is drawn when no legal sequence can produce checkmate. Repetition and move-count draws depend on history as well as the visible board. Under FIDE rules, threefold repetition and the fifty-move rule can support a claim; fivefold repetition and seventy-five moves by each side without a pawn move or capture trigger automatic draws, with checkmate taking precedence on the final move. Online interfaces may handle claims differently.

### Worked explanation

Two identical piece arrangements are not necessarily the same position for repetition if castling rights or legal en passant possibilities differ.

### Try it yourself

Given a FEN, identify the side to move, castling rights, en passant field, and halfmove clock. State which repetition facts are missing.

### Answer

FEN does not include the full repetition history. A tablebase exercise here starts with the documented halfmove clock and does not invent prior repetitions.

**Common mistake:** Declaring repetition from a single diagram.

**Recall:** What extra information can a draw decision need? Move history, rights, and the count since the last pawn move or capture.

## 07. The square of the pawn

**Goal:** Estimate whether a king can catch an unsupported passer.

For an unobstructed passed pawn racing without king assistance, imagine a square whose height is the pawn’s remaining distance to promotion. If the defending king can enter that square in time, it may catch the pawn. Account for whose turn it is, a pawn’s initial two-square option, obstacles, and checks. The rule is a quick geometric test, not a substitute for calculation when pieces or king support interfere.

### Worked explanation

A White pawn on a5 needs three moves to reach a8. A defending king’s route must reach the pawn or promotion square in time, and the side to move affects the race.

### Try it yourself

Count the pawn’s remaining moves and the king’s shortest legal route. Play the race out to verify the estimate.

### Answer

If the pawn starts on its original rank, include a legal two-square first move. If a king escort controls the route, the simple square rule may no longer decide it.

**Common mistake:** Counting squares while forgetting whose turn it is.

**Recall:** What is the rule of the square for? A fast estimate in a simple, unobstructed king-versus-pawn race.

## 08. Opposition is a way to gain access

**Goal:** Understand the purpose behind facing kings.

When kings face each other with one square between them, the player who does not have to move can often force the other king to give ground. This is direct opposition. Its value depends on which entry squares matter and whether a pawn move can transfer the turn. Do not seek opposition as a ritual when another route wins or when the relevant squares are elsewhere.

### Worked explanation

Kings on e4 and e6 contest entry through d5 and f5. If the side to move must step aside, the other king may advance, provided pawn attacks and board edges do not change the picture.

### Try it yourself

Set up facing kings, alternate the side to move, and identify which king can gain an entry square.

### Answer

Add a pawn and repeat. The result may change because a waiting pawn move can alter who must move the king.

**Common mistake:** Taking opposition without checking whether it helps the pawn advance.

**Recall:** What is opposition trying to achieve? Access to useful squares by forcing the opposing king to yield.

## 09. Key squares give the king a destination

**Goal:** Work backward from squares that ensure promotion.

In many king-and-pawn versus king positions, reaching a key square in front of the pawn allows the stronger king to force promotion. The relevant squares depend on pawn rank, file, and king placement. Rook pawns are special because the board edge reduces maneuvering room. Learn the method through exact positions: identify the destination, prevent the enemy king from blocking it, and preserve the necessary tempo.

### Worked explanation

For a central pawn, bringing the king ahead of the pawn can be more important than pushing it immediately. A premature push may give away the route or produce stalemate near promotion.

### Try it yourself

In a tablebase pawn exercise, compare a king advance with a pawn push. Identify which preserves the result and why the king route changes.

### Answer

Use the recorded exact result to check your conclusion, then explain it through access and timing rather than memorizing the engine’s first move.

**Common mistake:** Applying a memorized key-square picture to a rook pawn without adjustment.

**Recall:** Why identify key squares? They turn “support the pawn” into a concrete king-routing task.

## 10. Outflanking and distant opposition

**Goal:** Use more than one route around the defending king.

Distant opposition extends the idea of facing kings across a larger gap. Outflanking uses a route around the opponent when direct progress is blocked. The useful route may approach from the side rather than straight toward the pawn. Count king moves and consider whether the opponent can mirror your route. Board edges and pawn-controlled squares often decide which detour works.

### Worked explanation

If the defending king blocks a direct approach on the e-file, a route through the d-file may force it to choose between holding the pawn and allowing your king to penetrate.

### Try it yourself

For a pawn ending, compare a direct king route and a side route. Write the defender’s best response to each.

### Answer

A successful outflank gains an important square without allowing an equally strong counter-invasion.

**Common mistake:** Assuming the shortest geometric route is always the strongest chess route.

**Recall:** What does outflanking exploit? The defender’s inability to guard all useful entry routes at once.

## 11. Reserve tempi and pawn discipline

**Goal:** Save useful waiting moves until their timing matters.

A reserve tempo is a move that preserves the important position while changing whose turn it is to act. A pawn still on its starting square may have a choice of one- or two-square advances, but either move is irreversible and may create weaknesses. Do not spend waiting moves casually in king-and-pawn endings. Determine whether the pawn move preserves your winning route or defensive barrier.

### Worked explanation

Two king positions may look identical, yet one side has a harmless pawn move and the other does not. That spare move can decide who must surrender opposition.

### Try it yourself

List each pawn move available in an ending. Classify it as useful waiting move, structural commitment, or immediate tactical necessity.

### Answer

A pawn move is only a reserve tempo if it does not destroy the feature you need to preserve.

**Common mistake:** Calling any available pawn push a harmless waiting move.

**Recall:** Why save pawn moves? Their timing can transfer the obligation to move without changing the key king arrangement.

## 12. Zugzwang and triangulation

**Goal:** Recognize when passing would help but moving does not.

In zugzwang, the obligation to move makes the position worse. A king may triangulate through three squares to return to a similar position with the opponent to move. This works only when the king has a safe extra route that the opponent cannot copy without a concession. Identify the exact duty that fails when the defender must move.

### Worked explanation

A king guarding two entry squares may hold if it could pass. A successful triangle forces it to choose a square and abandon one of those entries.

### Try it yourself

Find a position where you would prefer the opponent to move. Test whether your king has a safe three-step route that changes the turn.

### Answer

Verify every response; not every triangle preserves the position. Pawn attacks and distant counterplay can spoil the maneuver.

**Common mistake:** Using the word zugzwang for any uncomfortable position.

**Recall:** What defines zugzwang? Having to make a legal move worsens the position compared with being able to pass.

## 13. Rook pawns and the wrong bishop

**Goal:** Recognize the drawing importance of the promotion corner.

A rook pawn has fewer adjacent king routes because the board ends beside it. In bishop-and-rook-pawn versus king, a bishop that does not control the pawn’s promotion corner may be unable to force out a defending king established there. The exact king placement still matters: if the defender cannot reach the corner in time, the pawn side may win before the defensive setup is achieved.

### Worked explanation

A White a-pawn promotes on a8, a light square. A dark-squared bishop cannot control a8. A Black king securely occupying that corner can create a familiar drawing fortress with correct play.

### Try it yourself

For each bishop-and-rook-pawn exercise, name the promotion corner’s color and the bishop’s color, then calculate whether the defender can reach the corner.

### Answer

Color identifies a possible mechanism; king access decides whether it is available in the actual position.

**Common mistake:** Declaring a draw solely from bishop color while the defending king is too far away.

**Recall:** What is the key defensive location? The rook pawn’s promotion corner, if the defender can establish itself there.

## 14. Outside and connected passed pawns

**Goal:** Use passers to distract or coordinate.

An outside passed pawn can draw the enemy king away from the main pawn group, allowing your king to enter elsewhere. Connected passed pawns can support one another, but their advance still depends on king access and blockade squares. Before pushing, calculate whether the opponent can sacrifice for one pawn and catch the other. The passer’s value includes the defensive attention it demands.

### Worked explanation

An a-pawn may be useful even if it will eventually be captured, because the defending king must travel far enough that your king wins kingside pawns.

### Try it yourself

Compare immediate promotion attempts with using the passer as a distraction. Count both kings’ routes after the expected capture.

### Answer

The correct plan depends on timing. A distant passer is not useful if the opponent creates a faster threat.

**Common mistake:** Pushing every passed pawn as far as possible without coordinating the king.

**Recall:** How can a passer help without promoting? It can divert defenders and open a route for the king elsewhere.

## 15. Pawn races: count moves and checks

**Goal:** Calculate promotion races to the resulting position.

Count legal moves to promotion for both sides, including captures, initial double advances, and king interference. Then ask whether promotion gives check and whether the new piece can stop the other pawn. Equal move counts do not necessarily mean a draw. The first queen may deliver a forcing check, skewer, or mating threat before the other side promotes.

### Worked explanation

A pawn promoting with check can gain a crucial tempo. A pawn promoting without check may allow the opponent to queen and create a tactical counterattack.

### Try it yourself

Write both races move by move, then continue at least one move after each promotion.

### Answer

Evaluate the resulting queen or piece ending rather than stopping when both pawns reach the last rank.

**Common mistake:** Counting only distance to the last rank and ignoring the checks that follow.

**Recall:** Why continue past promotion? The new piece’s checks and attacks may decide the race’s real result.

## 16. Active rooks and the passer’s rear

**Goal:** Understand why rook activity often matters more than a pawn.

A rook behind a passed pawn can support its advance or attack it as it moves away, which is why “rooks behind passers” is a useful guideline. It is not absolute: checking distance, king safety, and immediate tactics can justify another square. A passive rook tied to defense may have little scope, while an active rook can create enough counterplay to save a pawn-down ending.

### Worked explanation

A defending rook behind an enemy passer keeps attacking it along the file. If forced in front, it may be pushed backward and lose checking opportunities.

### Try it yourself

For a rook ending, compare an active checking square, a square behind the passer, and a passive defense of a pawn.

### Answer

Judge each by concrete checks, pawn security, and king activity. Do not choose the “correct-looking” square if it loses tactically.

**Common mistake:** Following the behind-the-pawn guideline while allowing a decisive king invasion.

**Recall:** What gives rook activity its defensive value? Checks, threats, and freedom from a single passive duty.

## 17. Cut off the king

**Goal:** Use a rook barrier to make king support arrive late.

A rook can prevent the enemy king from crossing a file or rank. In rook-and-pawn endings, cutting off the defending king can be more useful than checking it toward the pawn. Preserve the barrier while improving your king and pawn. The width of the cutoff and the pawn’s distance from promotion influence how much time the defender needs.

### Worked explanation

A defending king two files away from a central passer may struggle to approach if your rook controls the intervening file. An unnecessary check can let it step across the barrier.

### Try it yourself

Mark the rook’s barrier and the enemy king’s shortest route around it. Choose a move that improves your position without releasing the cutoff.

### Answer

If you must move the rook, identify what compensates for giving the king access. A checking move is not automatically progress.

**Common mistake:** Driving the defending king toward the square you were trying to keep it from reaching.

**Recall:** Why can a quiet rook barrier beat repeated checks? It restricts access and preserves time for your own king and pawn.

## 18. Lucena: shelter from checks

**Goal:** Learn the bridge-building idea in its proper setting.

The Lucena family of positions features a pawn on the seventh rank, its king in front, and a defending king cut off. The attacking rook can create shelter so the king escapes repeated checks and the pawn promotes. A common method places the rook on the fourth rank, brings the king out, and later interposes the rook against a check. Exact move order depends on the rook positions and checks.

### Worked explanation

The “bridge” is not a magic rook move. Its job is to stand between the checking rook and your king at the right moment, leaving promotion supported.

### Try it yourself

In a winning rook-and-pawn setup, identify the checking line, the king’s exit route, and the square where your rook could block the check.

### Answer

Verify that the defending king remains cut off and that the blocking rook cannot be captured without allowing promotion.

**Common mistake:** Trying to build a bridge in a position where the defending king is already close enough to stop the pawn.

**Recall:** What problem does the bridge solve? It gives the advancing king shelter from repeated rook checks.

## 19. Philidor: keep the king out, then check from behind

**Goal:** Understand a central rook-ending defensive method.

In the classic Philidor defense, the defending king stands in front of the pawn and the rook uses a rank barrier to stop the attacking king advancing. When the pawn advances far enough to remove that barrier’s usefulness, the rook switches to checking from behind. The timing prevents the attacking king from finding shelter in front of its pawn. Specific rook placements and pawn files require calculation.

### Worked explanation

For a White pawn moving upward, a Black rook on the sixth rank can deny the White king entry while the pawn is still behind it. Once the pawn reaches the sixth rank, rear checks become the defensive resource.

### Try it yourself

Identify the defender’s barrier rank, the pawn move that changes the plan, and the rear-checking route.

### Answer

The method needs an appropriately placed defending king and enough checking distance. If those conditions are absent, do not assume the position is drawn.

**Common mistake:** Switching to rear checks too early and allowing the attacking king to gain shelter.

**Recall:** What are the two phases? Restrict the attacking king, then use rear checks when the pawn advances.

## 20. Checking distance and the short side

**Goal:** Give a defending rook room to work.

Rook checks are more effective when the rook has enough distance that the attacking king cannot approach with tempo. In some rook-and-pawn defenses, the defending king belongs on the short side of the pawn while the rook checks from the long side. This leaves room for lateral checks. Treat it as a geometry to verify, not a universal placement rule for every rook ending.

### Worked explanation

A rook checking from only one file away may be chased immediately. With several files of separation, the king may be unable to approach without abandoning its pawn.

### Try it yourself

Count the checking distance and identify whether the king can attack the rook while keeping the pawn protected.

### Answer

If checking distance is inadequate, seek a different defensive setup, an exchange, or a timely pawn attack.

**Common mistake:** Giving checks that steadily bring the enemy king closer to the rook.

**Recall:** Why does checking distance matter? It determines whether the king can escape the checks by attacking the checking rook.

## 21. Minor pieces: blockade, color, and both wings

**Goal:** Match the piece’s strengths to the pawn structure.

A knight can blockade a pawn on a square where pawn attacks cannot chase it and can switch square colors. A bishop can influence distant wings quickly but remains on one color. With pawns on both wings, a bishop’s range may matter; in a closed structure with strong posts, a knight may excel. King activity and concrete pawn races can override these tendencies.

### Worked explanation

A bishop may stop a distant passed pawn while supporting its own king on the other wing. A knight may be better at occupying a protected square directly in front of a fixed pawn.

### Try it yourself

For a minor-piece ending, identify the blockade square, the pawn colors, and whether play exists on one wing or two.

### Answer

Then calculate whether the relevant piece can reach its job in time. A theoretically suitable piece can still be misplaced.

**Common mistake:** Declaring bishop or knight superiority without checking the actual routes and pawn threats.

**Recall:** What should guide a minor-piece comparison? Structure, targets, range, stable squares, and timing.

## 22. Queen endings: safety before arithmetic

**Goal:** Respect perpetual checks and promotion tactics.

Queen endings remain tactically demanding even with few pawns. King exposure can outweigh an extra pawn because checks may prevent progress indefinitely. Seek shelter, coordinate the queen with the king, and examine queen exchanges carefully. A passed pawn is strongest when advancing it does not abandon king safety or permit a checking skewer.

### Worked explanation

An extra pawn may be impossible to use if the king has no shelter from repeated checks. A queen exchange can solve that problem only if the resulting pawn ending is favorable.

### Try it yourself

Before advancing a passer, list the opponent’s best checks and identify your king’s shelter square.

### Answer

If no shelter exists, improve coordination or seek a favorable exchange. Do not assume that moving closer to promotion is automatically progress.

**Common mistake:** Evaluating a queen ending only by pawn count.

**Recall:** What often dominates queen-ending evaluation? King safety and the availability of forcing checks.

## 23. Choose the ending before exchanging

**Goal:** Make endgame entry a deliberate decision.

The critical endgame mistake often happens before the ending begins: an exchange removes the piece that was holding everything together. Before trading the last rooks or queens, visualize the remaining kings and pawns. Count races, check opposition or key-square access, and identify any fortress mechanism. If the result depends on one tempo, calculate it concretely.

### Worked explanation

A rook exchange may transform an active defensive position into a lost pawn ending because the enemy king gains the only entry square. Keeping rooks can preserve checking resources.

### Try it yourself

Take a position with an available exchange and compare the resulting ending with keeping the pieces.

### Answer

State the winning or drawing mechanism in each case. If you cannot identify one, continue analysis before committing.

**Common mistake:** Trading because fewer pieces feel easier, without checking whose task becomes easier.

**Recall:** What must be assessed before the final exchange? The concrete result and defensive resources of the ending it creates.

## 24. Endgame capstone: preserve the result

**Goal:** Practice both conversion and defense with exact feedback.

Use the mixed tablebase exercises to predict the result and then choose moves that preserve it. When several moves maintain a win or draw, explain their common purpose. When only one works, identify the lost tempo, king route, or tactical resource behind the alternatives. The goal is not to memorize arbitrary diagrams but to recognize the mechanisms that recur.

### Worked explanation

If both a king move and a pawn move look natural but only one keeps the win, compare the defender’s best response after each. The distinction often becomes clear when you count entry squares or promotion timing.

### Try it yourself

Complete twelve mixed endings, then replay three misses from the defender’s side. Keep a short note on the decisive mechanism.

### Answer

Repeat positions after a delay and explain them without reading the answer. Use exact results as a check on your reasoning, not a substitute for it.

**Common mistake:** Equating a single correct move with the ability to convert the whole ending against resistance.

**Recall:** What is the capstone skill? Preserve a justified result while understanding the mechanism and the opponent’s best defense.
