# azure-gem
adventurers seek a rare blue gem with mystical powers, facing challenges and uncovering ancient secrets along the way.
import azur

def random_azure_gem_event():
    events = [
        "You stumble upon a hidden cavern rumored to house the Azure Gem.",
        "A sudden storm uncovers an ancient map leading to the location of the Azure Gem.",
        "You meet a traveling merchant who claims to possess a shard of the Azure Gem.",
        "A mystical creature appears and offers to guide you to the Azure Gem's resting place.",
        "You decipher an ancient riddle that hints at the whereabouts of the Azure Gem."
    ]

    while True:
        input("Press Enter to encounter a new event related to the Azure Gem...")

        event = random.choice(events)
        print("\n" + event)

        choice = input("\nContinue your search for the Azure Gem? (yes/no): ").lower()
        if choice != 'yes':
            break

    print("\nYour search for the Azure Gem concludes.")
    print("Thank you for embarking on this adventure!")

# Start the random Azure Gem event generator
random_azure_gem_event()
