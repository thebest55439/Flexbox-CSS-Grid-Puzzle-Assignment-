<!DOCTYPE html>
<body>
    <div class="container">
        <h1>Puzzle Assignment</h1>
        <h2>Name: Mahirr Rubbinunan </h2>
        <h2>Puzzle Chosen: Butterflies</h2> 
        <h2>Assembled Puzzle</h2>
        <div class="puzzle-container">
            <!-- 4x4 grid of 16 pieces + 1 Fake piece -->
            <img src="images/butterfly/1" alt="Puzzle Piece 1" class="puzzle-piece">
            <img src="images/butterfly-piece-2.jpg" alt="Puzzle Piece 2" class="puzzle-piece">
            <img src="images/butterfly-piece-3.jpg" alt="Puzzle Piece 3" class="puzzle-piece">
            <img src="images/butterfly-piece-4.jpg" alt="Puzzle Piece 4" class="puzzle-piece">
            <img src="images/butterfly-piece-5.jpg" alt="Puzzle Piece 5" class="puzzle-piece">
            <img src="images/butterfly-piece-6.jpg" alt="Puzzle Piece 6" class="puzzle-piece">
            <img src="images/butterfly-piece-7.jpg" alt="Puzzle Piece 7" class="puzzle-piece">
            <img src="images/butterfly-piece-8.jpg" alt="Puzzle Piece 8" class="puzzle-piece">
            <img src="images/butterfly-piece-9.jpg" alt="Puzzle Piece 9" class="puzzle-piece">
            <img src="images/butterfly-piece-10.jpg" alt="Puzzle Piece 10" class="puzzle-piece">
            <img src="images/butterfly-piece-11.jpg" alt="Puzzle Piece 11" class="puzzle-piece">
            <img src="images/butterfly-piece-12.jpg" alt="Puzzle Piece 12" class="puzzle-piece">
            <img src="images/butterfly-piece-13.jpg" alt="Puzzle Piece 13" class="puzzle-piece">
            <img src="images/butterfly-piece-14.jpg" alt="Puzzle Piece 14" class="puzzle-piece">
            <img src="images/butterfly-piece-15.jpg" alt="Puzzle Piece 15" class="puzzle-piece">
            <img src="images/butterfly-piece-16.jpg" alt="Puzzle Piece 16" class="puzzle-piece">
            <img src="images/butterfly-piece-faulty.jpg" alt="Fake Piece" class="puzzle-piece Fake-piece">
        </div>

        <h2>Flex Container Properties Used</h2>
        <div class="properties-list">
            <p>The puzzle was assembled using the following CSS Flexbox properties:</p>
            <ul>
                <li><strong>display: flex;</strong> - Establishes the puzzle container as a flex container, enabling Flexbox layout for the puzzle pieces.</li>
                <li><strong>flex-wrap: wrap;</strong> - Allows puzzle pieces to wrap to the next row, creating a 4x4 grid layout for the 600x600px container.</li>
                <li><strong>width: 150px; height: 150px;</strong> - Sets each puzzle piece to a fixed size to ensure uniformity and proper alignment in the 4x4 grid.</li>
                <li><strong>flex: 0 0 auto;</strong> - Applied to puzzle pieces to prevent stretching or shrinking, maintaining their exact 150x150px dimensions.</li>
                <li><strong>display: none;</strong> - Applied to the faulty puzzle piece to hide it from the rendered view, ensuring only the 16 correct pieces are visible.</li>
            </ul>
            <p>The puzzle pieces are stored in an "images" folder within the project directory. The 16 pieces are arranged in the correct order to form the complete butterfly image in a 4x4 grid, with each piece being 150x150px. The faulty piece is included in the HTML but hidden using the <code>display: none;</code> property.</p>
        </div>
    </div>
</body>
</html>
