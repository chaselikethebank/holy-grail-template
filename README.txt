The Holy Grail of Templates 

1. tab ! return
2. launch server
3. add sections
    header
    sidebar
    main
    footer
4. style sections w bg colors
5. add responsive wrapper div for sidebar and main
6. add 12 divs with contents "item"
7. style main grid  
    grid-template-columns: repeat(auto-fit, minmax(270px, 1fr));
8. style children with main > div
9. vanishing sidebar
    @media (max-width: 700px) {
        sidebar {
          display: none;
        }

        .wrapper {
          grid-template-columns: 1fr;
        }
      }