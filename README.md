function searchEvents() {
    const eventsList = document.getElementById('events-list');
    eventsList.innerHTML = `
        <div>
            <h4>Concert A</h4>
            <p>Location: Venue 1</p>
            <p>Date: January 20, 2024</p>
        </div>
        <div>
            <h4>Concert B</h4>
            <p>Location: Venue 2</p>
            <p>Date: February 10, 2024</p>
        </div>
        <div>
            <h4>Theater C</h4>
            <p>Location: Venue 3</p>
            <p>Date: March 15, 2024</p>
        </div>
    `;
}
