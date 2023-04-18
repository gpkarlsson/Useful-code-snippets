# Useful-code-snippets

$(function () {
      
    });

<script
      src="https://cdn.jsdelivr.net/npm/dayjs@1.11.3/dayjs.min.js"
      integrity="sha256-iu/zLUB+QgISXBLCW/mcDi/rnf4m4uEDO0wauy76x7U="
      crossorigin="anonymous"
    ></script>
    
    

  <script
      src="https://code.jquery.com/jquery-3.5.1.min.js"
      integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0="
      crossorigin="anonymous"
    ></script>


let container = null;

// We want to render our React tree to a DOM element that is attached so that we can watch events
beforeEach(() => {
  // Setup a DOM element as the target
  container = document.createElement('div');
  document.body.appendChild(container);
});

afterEach(() => {
  // Cleanup on exiting to prevent this test from altering the results of future tests
  unmountComponentAtNode(container);
  container.remove();
  container = null;
});
