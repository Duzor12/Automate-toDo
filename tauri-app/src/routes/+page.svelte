<script lang="ts">
  
</script>

<main>
  <div class = "app">
    <div class = "left-column">
      <div class = "add-entry-area">
        <p class = "add-entry-area-text">Add Entry</p>
        <button class = "button add-entry-button">
          <img class = "add-entry-button-icon" src = "/icons/addButton.png" alt = "Add Entry" />
        </button>
      </div>

      <div class = "entries-area">
        <div class = "entry">
          <div class="entryContent">
            <div class="title-and-dueDate">
              <p class="entryTitle"> Call dentist </p>
              <p class="dueDate"> Today</p>
            </div>
              <button class = "expandEntryButton">
                <img class = "expandEntryButton-icon" src = "/icons/ExpandArrow.png" alt = "Expand Entry" />
              </button>
          </div>
        </div>
        <div class = "entry">
          <div class="entryContent">
            <div class="title-and-dueDate">
              <p class="entryTitle"> Pay electricity bill </p>
              <p class="dueDate"> Tomorrow</p>
            </div>
              <button class = "expandEntryButton">
                <img class = "expandEntryButton-icon" src = "/icons/ExpandArrow.png" alt = "Expand Entry" />
              </button>
          </div>
        </div>
        <div class = "entry">
          <div class="entryContent">
            <div class="title-and-dueDate">
              <p class="entryTitle"> Submit tax documents </p>
              <p class="dueDate"> 1 day</p>
            </div>
              <button class = "expandEntryButton">
                <img class = "expandEntryButton-icon" src = "/icons/ExpandArrow.png" alt = "Expand Entry" />
              </button>
          </div>
        </div>
        <div class = "entry">
          <div class="entryContent">
            <div class="title-and-dueDate">
              <p class="entryTitle"> Write report </p>
              <p class="dueDate"> 2 days</p>
            </div>
              <button class = "expandEntryButton">
                <img class = "expandEntryButton-icon" src = "/icons/ExpandArrow.png" alt = "Expand Entry" />
              </button>
          </div>
        </div>
        <div class="entry">
          <div class="entryContent">
            <div class="title-and-dueDate">
              <p class="entryTitle"> Grocery shopping </p>
              <p class="dueDate"> 3 days</p>
            </div>
            <button class = "expandEntryButton">
              <img class = "expandEntryButton-icon" src = "/icons/ExpandArrow.png" alt = "Expand Entry" />
            </button>
          </div>
        </div>
        <div class="entry">
          <div class="entryContent">
            <div class="title-and-dueDate">
              <p class="entryTitle"> Car maintenance </p>
              <p class="dueDate"> 5 days</p>
            </div>
            <button class = "expandEntryButton">
              <img class = "expandEntryButton-icon" src = "/icons/ExpandArrow.png" alt = "Expand Entry" />
            </button>
          </div>
        </div>
        <div class="entry">
          <div class="entryContent">
            <div class="title-and-dueDate">
              <p class="entryTitle"> Team meeting preparation </p>
              <p class="dueDate"> 6 days</p>
            </div>
            <button class = "expandEntryButton">
              <img class = "expandEntryButton-icon" src = "/icons/ExpandArrow.png" alt = "Expand Entry" />
            </button>
          </div>
        </div>
        <div class="entry">
          <div class="entryContent">
            <div class="title-and-dueDate">
              <p class="entryTitle"> Plan birthday </p>
              <p class="dueDate"> 1 week</p>
            </div>
            <button class = "expandEntryButton">
              <img class = "expandEntryButton-icon" src = "/icons/ExpandArrow.png" alt = "Expand Entry" />
            </button>
          </div>
        </div>
        <div class="entry">
          <div class="entryContent">
            <div class="title-and-dueDate">
              <p class="entryTitle"> Book vacation flights </p>
              <p class="dueDate"> 10 days</p>
            </div>
            <button class = "expandEntryButton">
              <img class = "expandEntryButton-icon" src = "/icons/ExpandArrow.png" alt = "Expand Entry" />
            </button>
          </div>
        </div>
        <div class="entry">
          <div class="entryContent">
            <div class="title-and-dueDate">
              <p class="entryTitle"> Review project proposal </p>
              <p class="dueDate"> 2 weeks</p>
            </div>
            <button class = "expandEntryButton">
              <img class = "expandEntryButton-icon" src = "/icons/ExpandArrow.png" alt = "Expand Entry" />
            </button>
          </div>
        </div>
        <div class="entry">
          <div class="entryContent">
            <div class="title-and-dueDate">
              <p class="entryTitle"> Renew gym membership </p>
              <p class="dueDate"> 3 weeks</p>
            </div>
            <button class = "expandEntryButton">
              <img class = "expandEntryButton-icon" src = "/icons/ExpandArrow.png" alt = "Expand Entry" />
            </button>
          </div>
        </div>
        <div class="entry">
          <div class="entryContent">
            <div class="title-and-dueDate">
              <p class="entryTitle"> Annual health checkup </p>
              <p class="dueDate"> 1 month</p>
            </div>
            <button class = "expandEntryButton">
              <img class = "expandEntryButton-icon" src = "/icons/ExpandArrow.png" alt = "Expand Entry" />
            </button>
          </div>
        </div>
      </div>

     

    </div>

    <div class = "right-column">
    </div>

  </div>
</main>

<style>


  /* CSS Reset */
  :global(*),
  :global(*::before),
  :global(*::after) {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    
  }

  :global(body) {
   overflow-y: hidden;
   overflow-x: hidden;
  }

  main {
    background-color: #111111;
    width: 100vw;
    height: 100vh;
    color: white;
    display: flex;
    padding: 16px;
  }

  .app {
    margin: 0px 16px 16px 16px;
    flex: 1;
    display: flex;
    flex-direction: row;
  }

  .left-column {
    flex: 3;
   /* border: 3px solid white; */
    display: flex;
    flex-direction: column;
  }

  .right-column {
    flex: 2;
   /* border: 3px solid white; */
  }

  .add-entry-area {
    font-family: Inter;
    color: #D7D6D6;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
   /* border: 3px solid green; */
    gap: 7.5px;
    padding: 8px;
  }

  .add-entry-area-text {
    font-size: 16.5px;
  }

  .button {
    position: relative;
    background-color: transparent;
    border: none;
    cursor: pointer;
    top: 2px;
  }

  .add-entry-button-icon {
    width: 20px;
    height: 20px;
    align-content: center;
    
  }

  .entries-area {
   /* border: 3px solid red; */
    flex: 1;
    overflow-y: auto;
    display: flex;
    flex-direction: column;
    gap: 5px;
  }

  .entry {
    height: 72px;
    min-height: 72px;
    background-color: #1A1A1A;
    border-radius: 0px;
  }


  .entryContent {
    display: grid;
    grid-template-rows: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
    padding: 8px 10px 10px 10px;
    width: 100%;
    height: 100%;    
    font-family: Aileron;
   
  }
  .entryContent .entryTitle {
    color: #CCCBCB;
    font-size: 18.5px;
  }

  .entryContent .dueDate {
    color: #7D7D7D;  
    justify-self: start;
    align-self: start;
    font-size: 13px;
    margin-top: 7px;
  }

  .expandEntryButton-icon {
    width: 15px;
    height: 15px;
  }

  .expandEntryButton {
    background-color: transparent;
    border: none;
    cursor: pointer;
    width: 15px;
    height: 15px;
    align-self: end;
    justify-self: end;
    grid-column-start: 2;
    grid-row-start: 2;
  }

  .title-and-dueDate {
    display: flex;
    flex-direction: column;
    grid-column-start: 1;
    grid-row-start: 1;
  }

/* Scrollbar styling for webkit browsers (Chrome, Edge, Safari) */
.entries-area::-webkit-scrollbar {
  width: 5px;

}

.entries-area::-webkit-scrollbar-track {
  background: transparent;

}

.entries-area::-webkit-scrollbar-thumb {
  background: #444444;  
  
}

.entries-area::-webkit-scrollbar-thumb:hover {
  background: #555555;
}
</style>
